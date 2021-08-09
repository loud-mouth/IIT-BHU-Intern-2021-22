# Microsoft SWE

**Name** Lakshya Singh
**Branch** Computer Science
**Course** B.Tech.
**Contact** [Twitter](https://twitter.com/1108King)

## Coding Round

There were two questions provided on Codility. The first one was an easy greedy + sorting question where you have to check by using available cranes can an object be moved from B to E. Just sort the `(crane position - length , crane position + length)` then keep on moving B till in reaches crane that has B and E in same range. Made sure to swap B if it's greater than E. That was that. Other one was also an easy greedy problem I don't remember it exactly.

## Interviews

### Round 1

#### Introduction

The interviewer asked me about myself. I had me finding the right answer for this for quite sometime now. I started off by personal info then what I do? which is [open source](https://github.com/king-11) contributions, [technical blogging](http://blog.manlakshya.tech/) and attending conferences. He seemed impressed as he told me that the usual answer he gets is I do Competitive Programming. I told him about how I started off with Windows XP and MS Office because obviously it was a Microsoft Interview. Also that my current stack is Visual Studio Code and Typescript both developed by MS again :smile:.

#### Knight and Destination

He starts of with question given a `n*m` chess board you have a Knight piece which needs to go from S to D in minimum number of moves. Find the count. I started off with a crude solution normal BFS and before coding I explained by approach to him. After a go ahead I coded the initial solution which was un-optimized. He asked me to do a quick dry run to show that it works. Next he asked me how would you do memoization which I implemented using a `n*m` array. Next he asked be how can I do pruning for the solution so that we don't go to longer paths if we already have a minimum implemented that just a if else check.

Finally he asked me since it was uninformed BFS what better can be done. I told him that Dijkstra's Algorithm will do the Job nicely but since it's a matrix we can use `A*` to do even better, I showed him why this will happen by defining the heuristic function as manhattan distance. I wasn't asked to code them just what and how better?

#### Why Microsoft?

Finally he seemed satisfied and asked me why Microsoft I also had it covered. My answer was that I wanted to empower new developers to build even better softwares using services like Azure, typescript and VSCode.

#### Anything Else?

He then asked me if I wanted to ask anything I asked him what he does and yeah that was all.

### Round 2

#### Level Order Traversal Binary Tree

This started off without my introduction this time he gave me a problem after introducing himself. The problem was finding printing level order traversal of a binary time. This time I was asked to code first then explain so I quickly went ahead and gave a solution using queue and yeah he seemed good with that. Although he stopped me midway whe I used `auto` in C++ because that surely makes it difficult for humans at the end humans should understand code not just machines.

#### Explain Any Project

Next he asked me what was the most difficulty project I did. I asked him does open source count and he as impressed and went on to tell me that at MS how much they value Open Source. So I told him in brief all the issues I had when I started off with [DXHeroes](https://github.com/DXHeroes/dx-scanner/pulls?q=is%3Apr+author%3A%40me+) and [PGRouting](https://github.com/pgRouting/pgrouting) also talked a bit about my [GSOC project](https://summerofcode.withgoogle.com/projects/#5343790958641152) which I didn't particularly tell as GSOC project just any open source contribution.

#### Talk about GSOC Project and Async I/O

As open source is huge he wanted to know just something specific he asked me about my GSOC Project at Chapel, which I cited to him as a productive parallel programming language. I told him that this was my first time working with C System Call, joked about getting my hands dirty with pointers, allocation, etc. ( he laughed too xD ). Finally told him about issues with I/O multiplexing which I was resolving using Asynchronous I/O. Async IO kinda hit him as something that college should don't have experience with and he himself worked on it so he told me like yeah that is a totally different game.

#### Anything else?

Finally my chance to ask I asked him what interns too whether their code makes into actual user apps.

## Crux

Some people had round 3 as HR or Technical mine wasn't so after interview I was sad but TPR told me that wasn't the case that I was eliminated so happy again.

And Yeah [Selected](https://www.linkedin.com/feed/update/urn:li:activity:6830505027312918529/) :hugs:
