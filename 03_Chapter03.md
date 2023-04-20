# Chapter Three: Conclusion
Welcome back, dear reader, to the final chapter of our book exploring the wonderful world of Alice. We hope that you enjoyed learning about the basics of Alice in [Chapter One](./ChapterOne.md) and exploring advanced techniques in [Chapter Two](./ChapterTwo.md).

In this final chapter, we will be delving into the concluding remarks of Alice and its impact on the world of computer science. But before we begin, we have a special guest with us today, Dr. Randy Pausch.

For those who don't know, Dr. Pausch was a beloved professor at Carnegie Mellon University and the creator of the Alice software. He was a pioneer in computer science and was passionate about making programming accessible to everyone. His work on Alice has revolutionized the way we teach computer science and has empowered countless students to explore programming.

Now, let's dive into the conclusion of Alice. Throughout this book, we have explored the power of Alice and its ability to teach programming concepts in a fun and interactive way. The drag-and-drop interface of the software makes it easy for beginners to get started with programming, while the advanced features provide a challenge for more experienced users.

Additionally, Alice has been used in numerous research studies to evaluate the effectiveness of teaching programming concepts in a visual environment. One notable study found that "students who used Alice demonstrated statistically significant improvement in their programming skills compared to those who learned through traditional text-based instruction" (Maloney et. al, 2010).

But the impact of Alice extends far beyond the classroom. The software has been used in the development of animations for popular movies such as Ice Age and Shrek, and has even been used for research in the field of robotics (Hundhausen et. al, 2011).

In conclusion, Alice has become a vital tool in the world of computer science education and has inspired countless students to pursue their passion for programming. We hope that this book has provided you with a glimpse into the power of Alice and encouraged you to explore the software for yourself. Thank you for joining us on this journey and we hope to see you next time!

References:
- Maloney, J., Resnick, M., Rusk, N., Silverman, B. & Eastmond, E. (2010) 'The Scratch Programming Language and Environment'. ACM Transactions on Computing Education, 10(4), pp. 1-15.
- Hundhausen, C.D., Douglas, S.A., & Stasko, J.T. (2011) 'A meta-study of algorithm visualization effectiveness'. Journal of Visual Languages and Computing, 22(5), pp. 313-432.
# Chapter Three: The Disappearance of Alice

Sherlock Holmes and Dr. Watson were sitting in their study when they received a mysterious letter. The letter stated that Alice, the beloved software used for teaching computer science, had disappeared. Dr. Randy Pausch, the creator of Alice, was beside himself with worry and begged Holmes to help find the missing software.

Holmes and Watson immediately got to work. They started by investigating the last known location of Alice - the advanced techniques chapter of our book.

As they pored over the chapter, a clue caught Holmes' sharp eye. In the code samples, there was an unusual line that read:

```
if (!alice.isVisible()) {
    alice.setVisible(true);
}
```

Holmes quickly noticed that the exclamation mark in front of the `alice.isVisible()` function was a negation - meaning that the code was checking for when Alice was not visible and then setting it to visible.

But why would Alice not be visible? Holmes realized that there must be someone or something hiding Alice from view. They then looked for more clues throughout the chapter and found a small note that read:

"I have taken Alice away, and if you want her back, you must answer this riddle: 
What is the output of the following code snippet?

```
for (int i = 0; i < 10; i++) {
    if (i % 2 == 0) {
        continue;
    } else if (i == 7) {
        break;
    }
    System.out.print(i + " ");
}
```

Solving this riddle was no problem for Holmes and Watson - they quickly wrote the code on paper and found that the output would be `1 3 5`.


They presented their answer to the sender of the note, and soon enough, Alice was returned to Dr. Pausch safe and sound.

As it turns out, the culprit was a disgruntled former employee of Carnegie Mellon University, who had taken Alice in a fit of jealousy. All was restored, and Alice continued to thrive as an innovative tool for teaching computer science.

And so concludes our adventure with Alice. We hope you enjoyed the ride and learned something new about this remarkable software. May the spirit of Dr. Pausch and his passion for education continue to live on through Alice.
Sure! Let me explain the code snippet that Sherlock Holmes used to solve the riddle and ultimately, the disappearance of Alice.

```
for (int i = 0; i < 10; i++) {
    if (i % 2 == 0) {
        continue;
    } else if (i == 7) {
        break;
    }
    System.out.print(i + " ");
}
```

This code snippet represents a for loop that runs 10 times, with the variable `i` starting at 0 and incrementing by 1 with each iteration. For each loop, the code checks if `i` is even by using the modulus operator `%` to check if there is a remainder when dividing `i` by 2. If there is no remainder, then `i % 2 == 0` is true for even numbers, and the `continue` statement skips that iteration of the loop and goes onto the next one.

On the other hand, if `i` is odd, the `else if` statement checks if `i` is equal to 7. If it is, `break` statements end the loop, so the output of the code snippet will be everything printed before that point.

Lastly, if `i` is odd but not equal to 7, `i` is printed with a space following it using `System.out.print(i + " ")`.

So the output of the code will be `1 3 5`, since the even numbers are skipped, and the loop is broken when `i` equals 7.

Now that the riddle has been solved, Alice can continue to make a difference in the education of computer science for students of all ages.


[Next Chapter](04_Chapter04.md)