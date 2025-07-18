# Challenge Name: Commitment Issues 

**Category:** General Skills

**Difficulty:** Easy

**Date Started:** July 16, 2025

**Date Completed:** July 16, 2025

**Writeup Published:** July 16, 2025

**Directions:** I accidentally wrote the flag down. Good thing I deleted it! You download the challenge files here: [challenge.zip](https://artifacts.picoctf.net/c_titan/75/challenge.zip)


 # Initial Observation: 
The direction said the flag was deleted, but what I learned in the Collaborative Development challenge, I could find the previous commit and see whether the flag was there or not. I thought it was going to be easy since I just learned a bunch of git commands.

 # Strategy (During the Challenge):
 1. Unzip the file
 2. Use ["git log"](https://careerkarma.com/blog/git-log/) to see the previous commits
 3. Find a suspicious-looking commit.
 4. Open that commit with ["git show"](https://www.atlassian.com/git/tutorials/git-show)
 5. Hopefully, find the flag in there

 # Tools Used:
 I did not use any extra tools since I knew the commands to find the flag. 

# Solution (What I Did During the Challenge): 
My strategy was correct: 

1. You unzip the file
2. Don't waste any time searching around the files, just type in "git log" and look at the previous commits.
3. There are only two commits: One of them says " Removing sensitive info."
4. Copy and paste that suspicious commit:
5. Use "git show" to open the commit
6. You will be able to see the flag when you do that

# Flag: 
The flag will be at the bottom of the old commit; it's quite easy to find

# Mistakes I made:
1. I wasted time using ls -a to search for the flag within the files when I knew the flag was somewhere in the commits 
   
# What I Learned:
This challenge just reinforced my knowledge of git commands: " git log" and "git show" 

