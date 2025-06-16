# Activity - Encyption/decryption using XOR

## Objective

Learn how to encrpyt/decrypt using a XOR logical operator.

## Prerequisites

- Before doing the lab, please review the lecture.

## Task
**Please note:** No need to write a code. Use paper and pencil and solve the following tasks.

### Encrypting the message
1. Select a secret "one English word" message. Keep it secret.
2. Convert the message into binary form. Each alphabet has a corresponding ASCII representation. Find out the [equivalent ASCII representation](https://www.asciitable.com/) of each character in the message.
3. Create a secret “one English word” key. For simplicity, use the same length of word key as the message. Then, repeat step two to convert the “secret key” into the binary form.
4. Apply XOR bitwise operation between the message and the key. The output will be the encrypted message in binary form. 
5. Convert the encrypted binary message into hexadecimal form for easy sharing.
### Decrypting the message
1. Use the "encrypted message" and the "secret key" and perform the bitwise XOR operation.
> **Remember to convert the encrypted message and the key into the binary form before applying the bitwise XOR operation**
2. Verify that the decrypted message is the same as the "plain text".
3. What strategies you will use to perform a bitwise XOR operation when plaintext and key have different lengths?

## What to submit?

1. Draw a flowchart of your thought process. I found this [online flowchart website](http://www.draw.io/) very useful. However, you can use any application of your choice. (1 mark)
2. What were your challenges in performing the lab (from design to the implementation phases)? (1 mark)
3. Encryption (4 marks)
4. Decryption (4 marks)

###################### Sophie's Work:

![IMG_4498](https://github.com/user-attachments/assets/be401770-a9db-45b5-a9cb-c4318b0d4814)
# I took a picture of my work on paper of my encryption. Please let me know if you cannot see it. Thank you.

![SophieLeeNumberingSystems drawio](https://github.com/user-attachments/assets/fd0ee9d8-a252-4bfc-8194-d1cf51b2191a)
# Flowchart Image. Please let me know if you cannot see it.

# I think what was difficult was when I was converting from decimal to binary , there were times when I mixed up the amount of 0s and 1s in the process. I also had to add a 0 in the front of each binary version of d, o, & g, in order to do the XOR operation while decryption. Aside from that, I felt that the implementation of my flowchart to my work was pretty straightforward.

## How to submit it?

- Upload the work in Github and clearly define your responses.
- Share the Github link

## Deadline

The deadlines are posted on the Syllabus as well as on Canvas.

## Rubric

- All the questions are answered, and the working code is submitted. (Grade 100%)
- Questions are partially answered, and the code has errors or incorrect output. (Grade 50%)

------

Last updated: Jun 2025 
