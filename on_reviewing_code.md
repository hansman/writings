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




------------------




# Reviewing Code

Code-Reviews sind eines der wichtigsten Tools, um Softwareteams miteinander zu synchronisieren. Sie ermöglichen Codern, ihr Wissen über die Codebasis und das System auszutauschen, Probleme zu erkennen, Stil durchzusetzen, Anleitung und Mentoring zu geben. Wenn dies richtig gemacht wird, werden Codeüberprüfungen eine Zusammenarbeit aufbauen, die Einbindung fördern, Codierer für den Codeigentum fördern und Organisationshierarchien überbrücken. In Anbetracht der Auswirkungen auf die Produktivität von Teams und Einzelpersonen hier einige Richtlinien, Empfehlungen und Hinweise zur Überprüfung von Code.

## courtesy
Halten Sie es unter allen Umständen freundlich. Zeigen Sie Höflichkeit in Ihrer Haltung und Ihrem Verhalten gegenüber dem Rezensenten. Ihre Denkweise sollte darin bestehen, eine integrative Kultur aufzubauen und zu versuchen, Probleme zu lösen, die über die Pull-Anforderung hinausgehen.

## explain why
Sie haben einen Punkt, der allzu offensichtlich erscheint? Möglicherweise fehlen Ihnen viele Informationen, um zu verstehen, warum sie auf diese Weise implementiert wurden. Fragen Sie nach dem Grund und erklären Sie immer, warum Sie etwas vorschlagen. Auf diese Weise kann der Rezensent Ihre Absicht verstehen.

## learn
Sie werden aufgefordert, Code zu überprüfen, da Sie auf einer gemeinsamen Codebasis zusammenarbeiten. In vielen Code-Reviews haben Sie weniger Erfahrung als der Reviewee. Sehen Sie sich die Code-Überprüfung als offenen Austausch an, um die Arbeit Ihrer Kollegen zu verstehen.

## provide support
Es ist nicht Ihre Aufgabe, Probleme für andere zu beheben, sondern es ist Ihre Aufgabe, Unterstützung bereitzustellen. Ihre Rezension sollte reich an Referenzen und gemeinsamen Erfahrungen sein, die den Rezensenten eher unterstützen als genaue Lösungen.


## give guidance
Code-Reviews sind eine gute Möglichkeit, andere zu beraten. Mit Ihrem Review haben Sie die Möglichkeit, mit gutem Beispiel voranzugehen, langfristig zu lösen und die Leistungen des Rezensenten zu feiern.

Hier einige Empfehlungen für respektvolle Code-Reviews.

### dos
- assume competence

Übernehmen Sie Kompetenz in Ihrem Gutachter. Der Prüfling hat einen Auswahlprozess durchlaufen, um mit Ihnen in dieser Codebasis zusammenzuarbeiten. Wenn Sie in Ihrem Gutachter keine Kompetenz vermuten, werden Sie dies auch nicht durch eine Codeüberprüfung beheben.

- discuss architecture before code review

Die Codeüberprüfung sollte keine Änderung der Architektur oder der grundlegenden Struktur einer Pull-Anforderung anfordern. Setzen Sie für strukturelle Änderungen die Erwartungen zusammen, bevor der Code implementiert wird.

- respond timely

Stellen Sie Code-Überprüfungen rechtzeitig zur Verfügung. Hinterlasse einen Kommentar, wenn du es nicht rechtzeitig überprüfen kannst.

- provide complete review

Stellen Sie eine vollständige Codeüberprüfung bereit. Das Ziel ist, Ihre Änderungsanforderungen in einem vollständigen Durchlauf bereitzustellen. Um den Punkt zu erreichen, helfen Code-Reviews dem Team, Impulse zu setzen, und ermutigen die Rezensenten zu mehr Eigenverantwortung.

- ask why

Sie verstehen den Code nicht oder schlagen vor, es anders zu machen? Fragen Sie, warum der Rezensent auf diese Weise umgesetzt wurde.

- make in person calls

Sie haben einen Punkt in Ihrer Rezension, der eine Hin- und Her-Diskussion erzeugt. Zeigen Sie sich kollaborativ, indem Sie einen kurzen Anruf zur Klärung einleiten.

- share insight

Erlauben Sie dem Rezensenten, von Ihnen zu lernen. Ein Rezensent ist möglicherweise neu in einer Codebasis und tut alles, um sich schnell anzupassen. Wenn Sie Erfahrung mit dem betreffenden Code haben, teilen Sie Ihre Erfahrungen großzügig mit.

- agree to disagree

Konzentrieren Sie sich auf die wichtigsten Aspekte und praktischen Details des Pull-Antrags und stimmen Sie zu, weniger wichtigen Details nicht zuzustimmen.

### donts

- don't ask for changes after the changes have been addressed

Versuchen Sie, nicht nach weiteren neuen Änderungen zu fragen, nachdem erforderliche Änderungen behoben wurden, es sei denn, etwas Unvorhersehbares und Kritisches wurde geändert. Ihre Überprüfung sollte abgeschlossen sein. Fordern Sie nicht mehr als (~) zwei Patches für die Pull-Anfrage an, sondern führen Sie anschließend zusammen oder lehnen Sie sie ab. Durch kaskadierte Codeüberprüfungen kann das Moment abgetötet und das Engagement entmutigt werden.

- don't comment on person but the code

Fügen Sie keine persönlichen Nachrichten in Code-Reviews ein. Sie sprechen mit der Codeänderung, aber nicht mit der Person. Halte dich ausschließlich an die Fakten.

- don't use extreme or negative language

Ihre Sprache ist wichtig. Es ist das Medium, das Ihre Rezension transportiert. Achten Sie darauf, ausschließlich positive und respektvolle Sprache zu verwenden. Eine emotionale Berührung sollte unbedingt vermieden werden. Ihre Codeüberprüfung sollte ausschließlich die Zusammenarbeit und das Engagement fördern. Negative Sprache oder sogar eine Schande für Menschen bringt keinen Mehrwert und ist ein wirksames Mittel, um den Rezensenten zu entmutigen.
