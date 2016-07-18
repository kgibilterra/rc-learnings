## Learnings

- I started going through the infamous Stanford Algorithms course.
- A new way to mentally/numerically represent log<sub>2</sub>n:
  - The graph below shows y=n and y=log<sub>2</sub>n. Understanding that y=n is a 1-1 relationship is simple enough, but I learned a new way of thinking about logarithms.
  - For each value of n (the x-axis) - divide it by 2 until you get to or below 1. The number of times you had to divide by 2 gives you the logarithm of it.
    - 32/2/2/2/2/2 = 1 (log<sub>2</sub>32 = 5)
    - 1024/2/2/2/2/2/2/2/2/2/2 = 1 (log<sub>2</sub>1024 = 10)
  - As you see, the input can be very large, but the output will soon become almost flat very quickly.
  - ![logn](/images/logn.png)
- Some interesting textbooks for learning more about algorithms:
  - Kleinberg/Tardos, Algorithm Design, 2005
  - Dasgupta/Papadimitriou/Vazirani, Algorithms, 2006
  - Cormen/Leiserson/Rivest/Stein, Introduction to Algorithms, 2009
  - Mehlhorn/Sanders, Data Structures and Algorithms: The Basic Toolbox (free online)

## Questions

- I vaguely remember Karatsuba Multiplication, but I didn't get to run through the proof as much as I'd like. Can anyone explain it? (or know of some nice resources for it?)
- I also do not remember proofs and discrete math like I wish I did. I think I'll start looking at the Mathematics for Computer Science class by MIT, but does anyone have any recommendations for that? I would love them!  


Feel free to [comment on the commit](https://github.com/kgibilterra/rc-learnings/commit/4cdfa7749cfa03f8c706f083f2955977606d9583) if you have any thoughts!
