# LZW (Lossless Compression Technique)

# **Summary:**

This small program makes use of one of the important text compression algorithms, **LZW**. It&#39;s used to encode ASCII Characters into compressed format with **a small size** , then you can **decode** the text again whenever you want into a readable format.

 ![](data:image/*;base64,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)

The program has **two options**. It can take the **text file name** from the user by running the main function in the file **LZW.java** then the compressed text will be in a file named **compressed.txt** , or you can run the **GUI app** from the file **GUI.java** and enter the text you want as in the following picture.
You can find more infromation for **how this algorithm works** at this **PDF** : [http://www.learngroup.org/uploads/2015-10-27/Intro,\_LZ77,\_LZ\_78,\_LZW\_Leangroup\_org.pdf](http://www.learngroup.org/uploads/2015-10-27/Intro,_LZ77,_LZ_78,_LZW_Leangroup_org.pdf) starting from **page 79**.

The project is built using **Java, IntelliJ.**