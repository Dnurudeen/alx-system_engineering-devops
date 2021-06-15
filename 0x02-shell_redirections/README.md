Project 0x02-shel _redirection

0. Hello World ----Ans: echo "Hello, Word"

1. Confused smiley -----Ans: echo ("\"Oo'")

2. Let's display a file ----Ans: cat /etc/passwd

3. What about 2 ----Ans: cat /etc/passwd /etc/hosts

4. Last lines of a file ----Ans: tail -10 /etc/passwd

5. I'd prefer the first ones actually ----Ans: head -10 /etc/passwd

6. Line #2 ---Ans: head iacta --lines=3|tail --lines=1

7. It is a good file that cuts iron without making a noise ----Ans: echo "Holberton School" > \\\*\\\\\'\"Holberton\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)

8. Save current state of directory -----Ans: ls -la > ls_cwd_content

9. Duplicate last line -----Ans: tail iacta --lines=1 >> iacta

10. No more javascript ----Ans: find . -name "*.js" -type f -delete

11. Don't just count your directories, make your directories count ----Ans: find -mindepth 1 -type d | wc -l

12. What's new -----Ans: ls -t|head -n 10

13. Being unique is better than being perfect ---Ans: sort|uniq -u

14. It must be in that file ----Ans: cat /etc/passwd|grep root

15. Count that word ----Ans: cat /etc/passwd|grep bin| wc -l

16. What's next? -----Ans: cat /etc/passwd|grep root -A 3

17: I hate bins ---Ans: cat /tc/passwd|grep -v "bin"

18. Letters only please ----Ans: cat /etc/ssh/sshd_config|grep ^[[:upper:][:lower:]]

19. A to Z -----Ans: tr Ac Ze

20. Whitout C, you would live in hiago ----Ans: tr -d cC

21. esreveR ---Ans: rev

22. DJ Cut Killer ----Ans: cut -d: -f 1,6 /etc/passwd | sort -d