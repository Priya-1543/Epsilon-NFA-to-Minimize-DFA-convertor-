# Epsilon-NFA-to-Minimize-DFA-convertor

In computation theory, dealing with a large number of states and complex transitions in an epsilon-NFA can be challenging. To simplify this
process, we’ve developed a website using the Django framework. It takes Epsilon-NFA states and transitions as input, converting them into a DFA using a graph traversal algorithm with optimization using memorization to avoid repetitive calculation. The DFA is further minimized using the table-filling method. The output at each stage is displayed using a graph visualizer. This website is useful for both academic and professional purposes.

When you first load the site it will show you following page where you can add details of your Epsilon-NFA as mentioned in example of each input field.

![img1](https://github.com/user-attachments/assets/b741c7bc-7356-4aae-8407-042726a25e98)


Once you enter all the details click on "Submit".  You will be redirected to page where you can specify transistion of your Epsilon-NFA by means of simple drop-down menue as shown below.

![img2](https://github.com/user-attachments/assets/8b6e69de-8be9-4b61-8e64-ed36114e9cad)


Here drop-down for state shows possible states you entered previously and forsymbol it will show symbol you entered in language field.

![img3](https://github.com/user-attachments/assets/37d093f5-be95-42e6-abb8-57b9ea7c8080)


Once you enter all transistion click on "show result". You will be redirected to result page where you can see your Epsilon-NFA, NFA, DFA and Minimized DFA in graphical form.

Epsilon-NFA

![img4](https://github.com/user-attachments/assets/a80b0e54-3312-4d55-ad07-e54c64b8985b)


NFA

![img5](https://github.com/user-attachments/assets/dafbaedd-b2f6-4ab2-bde4-28967b15037f)


DFA

![img6](https://github.com/user-attachments/assets/712b088c-6d35-4acc-87b4-72c7bb237290)


Minimized-DFA

![img7](https://github.com/user-attachments/assets/69e52a6b-1c2d-4b34-aab4-133b931e1fca)
