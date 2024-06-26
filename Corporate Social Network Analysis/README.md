## Explanation

[**Lazega Dataset**]{.underline}: from a network study of corporate law partnership. - Includes (among others): measurements of networks among the 71 attorneys (partners & associates) of the firm

1.  Strong-coworker network
2.  Basic advice network
3.  Friendship network
4.  Indirect control network

Dataset used to identify social processes such as: bounded solidarity, lateral control, quality control, etc among peers.

## Questions asked for each network

1.  [Strong-coworker network]{.underline}: "Because most firms like yours are also organized very informally, it is difficult to get a clear idea of how the members really work together. Think back over the past year, consider all the lawyers in your Firm. Would you go through this list and check the names of those with whom you have worked with. $$By"worked with" I mean that you have spent time together on at least one case, that you have been assigned to the same case, that they read or used your work product or that you have read or used their work product; this includes professional work done within the Firm like Bar association work, administration, etc.$$"

2.  [Basic advice network]{.underline}: "Think back over the past year, consider all the lawyers in your Firm. To whom did you go for basic professional advice? For instance, you want to make sure that you are handling a case right, making a proper decision, and you want to consult someone whose professional opinions are in general of great value to you. By advice I do not mean simply technical advice."

3.  [Friendship network]{.underline}: "Would you go through this list, and check the names of those you socialize with outside work. You know their family, they know yours, for instance. I do not mean all the people you are simply on a friendly level with, or people you happen to meet at Firm functions."

4.  [Indirect control network]{.underline}: using as base the links from the advice network, we have generated a set of attributes to the links based on the tenure and the status of the lawyers. This network must be used to study the De Groot model for learning in networks.

## Attributes in the three networks:

1.  status (1=partner; 2=associate)
2.  gender (1=man; 2=woman)
3.  office (1=Boston; 2=Hartford; 3=Providence)
4.  years with the firm
5.  age
6.  practice (1=litigation; 2=corporate)
7.  law school (1: harvard, yale; 2: ucon; 3: other)

learning_advice network contains the edges attribute: 8. weight (0-1) the weight of the importance taht the actor in the row of the adjacency matrix gives to the opinions of the actor in the column - In adjacency matrix - sum along rows is 1, along the columns is any number.
