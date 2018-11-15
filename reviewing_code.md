# Reviewing code

Code reviews are one of the most powerful tools to keep software teams in sync. They allow coders to exchange their knowledge about the codebase and the system, catch problems, enforce style, give guidance and mentoring. If done right, code reviews will build collaboration, encourage engagement, foster coders on code ownership and bridge organizational hierarchies. Given its impact on the productivity of teams and individuals here some guidelines, dos and donts on reviewing code.

## courtesy
Keep it friendly under all circumstances. Show politeness in your attitude and behavior towards the reviewee. Your mindset should be to build an inclusive culture and try to help solve problems beyond the pull request.

## explain why
You have a point that appears all too obvious? Very possible you are missing a lot of information required to understand why it has been implemented this way. Ask why and always explain why you suggest something. This way the reviewee can understand your intention.

## learn
You are requested for reviewing code because you are collaborating on a shared code base. In many code reviews you will have less expertise than the reviewee. See the code review as an open exchange to understand your peers work.

## provide support
It is not your job to fix problems for others but its your job to provide support. Your review should be rich of references and shared experiences that support the reviewee rather than precise solutions.

## give guidance
Code reviews are a great way to mentor others. With your review you have an opportunity to lead by example, solve for the long-term and celebrate the reviewee's achievements.



Here some dos and donts for respectful code reviews.

### dos

- assume competence

Assume competency in your reviewee. The reviewee has gone through a selection process to collaborate with you in this code base. If you assume no competency in your reviewee you will not fix it with a code review either.

- discuss architecture before code review

The code review should not request a change on the architecture or fundamental structure of a pull request. For structural changes, set expectations together before the code gets implemented.

- respond timely

Provide code reviews timely. Leave a comment if you can't review in time.

- provide complete review

Provide a complete code review. The goal is to provide your change requests in one complete pass. To the point code reviews help the team to build momentum and encourages reviewees to more ownership.

- ask for why

You don't understand the code or suggest to do it differently? Ask why the reviewee implemented in this way.

- make in person calls

You have a point in your review that generates a back and forth discussion. Show yourself collaborative by initiating a quick call to clarify.

- share insight

Allow the reviewee to learn from you. A reviewee might be new to a codebase and is doing its best to adapt quickly. If you have experience with the code in question be generous sharing your experience.

- agree to disagree

Focus on most important aspects and practical details of the pull request and agree to disagree on less important details.


### donts

- don't ask for changes after the changes have been addressed

Try to not ask for additional new changes after requsted changes have been addressed unless something unforeseeable and critical changed. Your review should be complete. Don't request more than (~) two patches on the pull request but merge or reject after that. Cascaded code reviews can kill momentum and discourage engagement.

- don't comment on person but the code

Don't include personal messages in code reviews. You are speaking to the code change but not to the person. Stick exclusively to the facts.

- don't use extreme or negative language

Your language matters. It is the medium that transports your review. Make sure to use exclusively positive and respectful language. An emotional touch should be absolutely avoided. Your code review should exclusively foster collaboration and engagement. Negative language or even shaming people is not adding value and is an effective way to discourage the reviewee.

