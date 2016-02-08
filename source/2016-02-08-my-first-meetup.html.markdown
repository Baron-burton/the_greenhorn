---
title: My First Meetup
date: 2016-02-08
tags: meetup
---

It was at the evening of my first meet-up with NWRUG (North West Ruby User Group). I was excited. By encouraging myself to join this group I was opening myself up to a great deal of insight into what it takes to become a developer. I knew this was the start of something good for me.

  I walked into the building where the meet-up was being held (MadLab). On the first floor was NWRUG. I walked towards the table and as I began to set my things down I was quickly acknowledged and welcomed to the group. I was relieved that it was the members of the group who spoke up first because at the time I felt like I was in a completely alien environment. I almost didn’t want to introduce myself because I didn’t want to interrupt anyone’s conversation (the silly things you think when you’re meeting new people right?).  

With it being a hack night and not having a computer I thought I’d quietly watch people work through the problems, just observe and absorb. The theme for the night was a cryptographic challenge, another thing I knew nothing about. As much as I was content with just sitting in the back for my first night the members of the group were keen to have me paired up so that I could have a go at the challenge.   

The goal for the challenge was to use Ruby code to decrypt a message using two types of ciphers. Firstly, we were given an unreadable mass of letters that was encrypted using a Vigenere cipher and a mix of letters that had been encrypted using a Caesar cipher. We had to solve the Caesar cipher to reveal the keyword that would help solve our Vigenere cipher. So what are these ciphers? Good question!  

A Caesar cipher is a system of encryption wherein every occurrence of a particular letter is replaced by what is known as a cyphertext letter.Basically, you have two alphabets. In order to crack the Caesar cipher you need to know the shift associated with the cipher. For instance, a shift of 5 would mean the letter A in the cipher actually represents the letter F. You apply this shift to your coded text to reveal the secret message.  

After we had solved our the Caesar cipher it was on to the Vigenere. This particular cipher is quite tricky because there’s no simple one-to-one mapping of two texts. So how does it work? 

Imagine that each letter of the alphabet represents a number starting with A = 0, B = 1, C = 2, etc. Knowing this we can then use a keyword to sneakily encrypt an entire message. As an example, let’s say our Caesar cipher keyword is “SURPRISE” and the message we want to encrypt is “Attack at first light”. Each letter of our keyword represents it’s own shifted alphabet so S is a shift of 18, U is a shift of 20 and so on. The trick is to apply the keyword on top of the text that you’re looking to encrypt like so;

Keyword:  SURPRI SE  SURPR   ISESU 
Message:  ATTACK AT  FIRST   LIGHT

This results in the cipher: SNKPTS SX XCIHK TAKZN. Pretty neat!  

Although my teammate and I didn’t crack the final cipher, the night was still a resounding success for me. I was engrossed in trying to solve the problem and was having a blast failing and trying something new.   

A thought that occurred to me on the night was that we were using the Ruby language in a way that I’d never even thought of. Previous to tonight, I thought that Ruby could only be used for specific things to do with web development, yet here we were messing around with cryptography challenges. 

That evening forced me to keep an open mind about the things I could try and do with Ruby code and definitely reiterated the fact that there was obviously so much more that I needed to learn. There was a long road ahead but I had now joined a friendly group of like minded people who I could learn from.