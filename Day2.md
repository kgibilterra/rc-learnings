## Learnings

- I worked through mergesort and inversion sort. Came up with some complex algorithms until I realized passing in the length of the array would remove a ton of the complexity while merging!
- The Guiding Principles of Algorithm Analysis (for Stanford):
  1. “Worst-case analysis"
  2. We won’t pay much attention to constant factors, lower-order terms
  3. Asymptotic Analysis (look at large inputs)
- What is an inversion? If you have an array [1 3 5 2 4 6], how many switches (inversions) do you have to make for it to be in [1 2 3 4 5 6] order?
  - in this case, three: [5 2] [3 2] [5 4]
- The largest number of inversions for an array is: ![inversions](http://bit.ly/29Yl4EE)

## Questions

- I want to get better at not following rabbit holes when I am doing algorithms. I should have realized I could have used an additional parameter to solve merge sort. Any tips for breaking yourself out of a cycle like that?
- After pushing to github, can I rebase an old commit with a code change, but keep it to that commit with the comments still in place for it?
