# Executive Summary

Lab 2 is an introduction to hardware and data representation. We look at various hardware components as well as how data is represented in software. This unit has been incredibly helpful to me as I did not know much about all the different parts of a computer and what each does to contribute to the overall functions.

## Hardware

### Hardware: Hard Drives and Memory

When examining the performance of a hard drive, the rotational speed of the platters is a significant component because it directly impacts the latency and disk transfer rate. Latency is the average time for the sector being accessed to rotate into position, and it is calculated from the spindle speed. The disk transfer rate, on the other hand, is the speed at which data is transferred to and from the disk media, and it is usually calculated in megabytes per second (Mbps). When analyzing the performance of a hard drive, the latency is how long it takes the hard drive’s read/write head to find he physical location of a piece of data. The transfer rate is the speed at which the host computer can transfer data across the interface to the CPU.

A solid state drive is a storage device that uses solid state memory to store data. It improves on a traditional hard drive because it addresses many of the timing and structural problems. With a traditional hard drive, there are too many moving parts that are both fallible and slow. But with solid state drives, there are no moving parts, spinning platters, or moving heads. Data is split and stored into memory, then accessed almost instantaneously using unique system-wide addresses. Solid state drives are more expensive, but there are preferred over traditional drives because of this speed as well as greater stability.

Increasing Random Access Memory (RAM) makes the computer run faster because it increases the speed at which memory transfers information to other components. More data can be stored so we do not need to swap data back and forth between the RAM and hard disk. Finally, it allows the instructions from more programs to be held in RAM and so multitasking is easier. Essentially, increasing RAM increases your digital countertop.

The difference between 32-bit and 64-bit data paths is that a 32-bit path can access 2 to the power of 32 memory addresses while a 64-bit path can access 2 to the power of 64 memory addresses. A 64-bit processor can access over four billion times the physical memory of a 32-bit processor.

### Hardware: ALU and the Control Unit

The arithmetic logic unit does all the calculations for the control unit. The control unit gets its data from the RAM and breaks that data down for the other components. The ALU has two inputs which, according to whatever the RAM tells the control unit to do, can be added, subtracted, or compared to each other. So the RAM instructs the control unit which then directs the ALU to do the specific operation using the two inputs. 

The ALU does not always need an output, but in situations where the inputs are added or subtracted, there will be an output using a register. A register stores a number temporarily while instruction is being processed, and it’s more useful than a RAM in this case because it is inside the CPU and therefore faster. When the ALU sends the output to the register, it will be saved when the control unit turns on the register’s set wire and then the enable wire moves the number out of the register to get the output. Then the register will move the output to the CPU’s bus, a group of wires that connect multiple components. This bus has multiple registers with their own instructions, set and enable wires, so the control unit will then save the number to the register it wants it to go to using the set wire and then clear the bus. Because you can only have one number on the bus at a time, the ALU uses a temporary register for the second input which will only output to the ALU. 

If no output is needed, the ALU will instead send a flag back to the control unit to help decide what to do next. Each flag turns on and on based on which conditions are true, such as if both inputs are the same or if one is larger than the other. The instruction address register then retrieves the next instruction from the RAM for the control unit to work on next.

### Hardware: CPU, Input and Output

Using a self-check-out register at a grocery story is a great example of how each of these parts of a computer works. First, you input the information you need, such as the items you want to buy at the register, for the computer to convert into binary code. In this example, the input comes from the item scanner. Next, the register stores the items and prices of everything you scan into memory. The central processing unit (CPU) then processes what you have inputted and stored, and then calculates the total cost of all of your items. Finally, the output is both the screen that gives the customer a summary of the transaction as well as the device that prints a receipt.

### Hardware: Logic Gates and Circuits

A truth table is a great way to summarize logic gates.They show the output you get for every possible input. It reminds me of a Punnett square, a diagram in genetics used to predict possible genotypes. Similarly, a truth table shows a breakdown of a logic function by listing all possible values that function can attain. There are three basic operations, NOT, OR, and AND. There is also XOR (exclusive OR) and NAND (AND with outputs reversed) as well. So if input 1 and input 2 are zero, AND would show the output as 0. If either input 1 or input 2 was 0, the AND gate would also show 0. If both inputs were 1, the output would also be 1. Therefore, with a NAND gate, the outputs would all be reversed. 0 and 0 would output 1, inputs of 1 and 0 would also output 1, but two inputs of 1 would output 0. 

### Hardware: IEEE - Ethically Aligned Design

he institute of Electrical and Electronics Engineers (IEEE) is the world’s largest technical professional organization  It was originally formed in 1884 to support professionals and to aid them in their efforts to use technology and innovation to help humanity. Many inventors like Thomas Edison and Alexander Graham Bell led IEEE to focus on electrical engineering, as well as wired communication.

Today, especially with the emergence of artificial intelligence, ethical decision-making in technology and device design is of utmost importance. If you design an AI system unethically, human lives will suffer as a result. IEEE has focused on AI ethics in a big way recently, and companies like IBM and Amazon helps those teams establish best practices for designing and developing AI devices in a way that helps humanity rather than harms it.

The five areas of ethical focus are accountability, value alignment, explainability, fairness, and user data rights. IEEE also delves deeper into design ethics in a course called Artificial Intelligence and Ethics in Design. They make sure companies are using AI for a societal purpose and not just for profit. They also make sure companies are protecting consumers’ data and not exchanging privacy for profit. People distrust Amazon’s Alexa for this very reason, and IEEE’s core focus revolves around using AI technology like Alexa in a way that is not harmful to society.

## Data Representation

### Data Representation: Numeric Conversions

The difference between decimal, binary, and hexadecimal numbers is best described by looking at the base of each, which is either the number of different digits or combination of digits and letters that represent a number. A decimal is base 10 so you can represent any number using 10 digits [0-9]. Binary is base 2, meaning you can only use a 0 or a 1 to represent a number. Hexadecimal is base 16, so you can use 10 digits [0-9] and 6 characters [A-F] to represent a number.

### Data Representation: Hexadecimal Color Representation

In a RGB color space, #ab00ff represents 67.1% red, 0% green, and 100% blue. In a CMYK color space, it is composed of 32.9% cyan, 100% magenta, 0% yellow and 0% black. 

When considering accessibility for web sites, there should be shades that provide enough contrast between the content and the background, especially for those with low vision impairments and color deficiencies. A contrast ratio of 4.5:1 is the minimum WCAG 2 standard for regular sized text. The goal is to get the highest level in crucial areas across the entire site. Alternatives to increase accessibility is to increase the font, provide tools for users to adjust colors of your site on the front-end, and to steer clear of text-based images in favor of text whenever possible.

This color is highly problematic because this shade does not provide enough contrast between content and background in many cases for those with color blindness deficiencies. When testing this shade with a contrast checker, I could not find any accompanying background/foreground shades that give a contrast ratio of 4.5:1 or better.

# Conclusion

Understanding how all the various hardware components work and how they interact with each other was the focus of this unit. We also analyzed data representation and how to convert from binary to decimal and vice versa. Although I am much more interested in programming and software, hardware focused units such as this one, as well as binary data representation and conversion certainly contribute to a more micro understanding of what programmers do on a daily basis.

