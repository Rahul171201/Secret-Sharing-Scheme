# INTRODUCTION
Many applications require exchange of information over the internet in a secure manner. The main objective of this project is to develop a k out of n fast secret sharing scheme to transfer secret images (using encryption algorithms) using n number of shares such that any k out of the n shares can be combined to reconstruct the secret images using a valid key and disallowing revelation of the secret image if the number of shares falls below k. Hence this ensures authentication of share holders and
eradicates the problem of misusing the shares. The regenerated image has better visual quality and the recovery time is also very less as it requires simple addition and XOR operations. This algorithm is designed such that it supports both gray and color images.

![image](https://user-images.githubusercontent.com/70642284/197492927-8d346646-0ae7-4319-b57f-70e8b392ceb8.png)

#  CHALLENGES
* There are various algorithms already implemented which involve the dividing the secret into n shares and then recreating the secret using any of the k shares.
* However one of the challenges regarding the algorithm is that if anybody steals the share of any participant, then he may be able to access the secret information.
* Also there may not be any form of authentication for the participant who actually has the share. Hence the secret is very much vulnerable.

# PROPOSED ALGORITHM
The proposed algorithm not only ensures the authentication of each particiapnt but also provides additional security for each of the shares.

