# UniCycle
Public good on-chain global learning certification (ETH Global Istanbul 2023 Submission).
For both teaching methods:
- by university credits issued tokens
- by schools claiming an NFT for students evaluated succesfully
  
## Other Repos (in continuation):
College Credits/Course Registration and university pass: https://github.com/avdheshcharjan/unicycle-course-registration
Token Transfer to other colleges: https://github.com/avdheshcharjan/unicycle-token-transfer
  
## Credit Transfer in Education

Problem we want to solve: 
- Months of credit validation administrative process to validate university credits from one to another.
- Provide a certification solution to non acredited schools, by examining the student and certify it with an NFT.
- Give an oportunity to ALL students to demostrate their learnings and reduse inequality.  


## Summary

UniCycle is a  transferring credits to students from Universities as well as non acredited schools. In the case of universities, credits are converted into tokens and securely transferred using public key encryption and hashing. Upon course completion, credits are converted into tokens and stored in the blockchain wallet.

Presentation link: https://www.canva.com/design/DAF0lPPDY1g/0ij1brwPui5SEm1kLuNi7Q/edit?utm_content=DAF0lPPDY1g&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## State of the art academic literature

The project aligns with ongoing initiatives in applying blockchain to education. Earlier models tackled challenges like preventing certificate forgery, facilitating credit transfers, and enhancing data security. Blockchain-based systems bring forth advantages such as transparency, efficiency, and security in the storage and validation of academic credentials.

## Real requested solution from an University 



## User Path

![Main goal](https://github.com/avdheshcharjan/UniCycle/assets/114303420/755e9369-5496-4752-9a38-586d9cb87d3e)

![Achieved](https://github.com/avdheshcharjan/UniCycle/assets/114303420/6af05c42-ff1b-4cc3-be19-9accd5f147df)

We are going to divide the explainantion by the two users:
From the school, or a non acredited learning academy case, the university is going to publish their courses, the student then can register to those courses. A Student will recieve a registartion attestation enrolment pass, proving that he is well enrolled into the course. At the end of the course he will take our online quizz and if he passes, he will recieve an NFT, thus beeing able to demostrate that he has well learned the content from the course.
On the other hand, the universities will publish their courses, the student will enroll and recieve a course registration attestation pass as well. He will make some exams and if he passes he will recieve the credits (tokens) from the course, beeing able to get to his objective of graduating, demosytrate his learnings and validate them to another university if he changes. 

To do, further:
However, we didn't had time to deploy the mulisig from the teacher, administartion and director to activate the rewards. As neighter, to store the full content of the course description and project done. 

## Implementation

The Ethereum smart contract is programmed in Solidity, presenting an ecosystem for higher educational organizations. Tokens, ownership transfers, and secure math functions ensure the integrity and security of the system.

#### Replay Attack

The system resists replay attacks, where attackers seize and replay messages to disguise their identity.

#### Collusion Tamper Attack

The proposed scheme updates data periodically to public Ethereum, reducing the likelihood of collusion tamper attacks.

## 6. Conclusion

The ecosystem for credit transfer and a evaluation certification in education provides in a long term a secure, transparent, and efficient solution. Through smart contracts and decentralized storage, we ensure the integrity of academic credentials and facilitate seamless credit transfers. The system's resilience to various attacks and scalability make it a robust solution for the future of education. Enabling a student to demostrate his academic learning skills even not having went to higher education institutions.  
