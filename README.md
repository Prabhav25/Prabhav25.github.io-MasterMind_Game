
This game is created in metaverse studio.gometa.io and in order to play this game you have to download the Metaverse - Aurgmented Reality app in your phone and just copy the link (https://mtvrs.io/ToughPlainSulphurbutterfly) or scan the QR code from (https://studio.gometa.io/discover/me/c3d788e1-3695-4ed9-a8dd-027aae576cc7).

So here i am creating a game which containes some questions and if all the questions answered correctly in the given time then you will get a surprise.


1st question---------------

So firstly add a character scene 1 in which add a text , add a acharacter and add a START button.

Now to track the points we will add a property block(Set experience property) whose initial value is set to 0.

So for each question we will have a character scene and we will add a point each time a person gets the question correct.

So when you give the answer right then the increment block will increase the value by 1 and display it in the scene 3 , incase the answer is not correct then without incrementing it will directly transit to scene 3.



2nd question---------------

So we add a text input scene that is scene 4, to ask the next question.

We add a check text response block that will check the entered text or the answer of the question is correct or not.

If the answer is correct then with the help of increment block the value increases by 1 and gets displayed in the character scene that is scene 5

If the answer is incorrect then without incrementing it directly gets transit to scene 5.



3rd question-----------------

So we add a character scene that is scene 6, to ask the next question.

If the answer is correct then with the help of increment block the value increases by 1 and gets displayed in the character scene that is scene 7

If the answer is incorrect then without incrementing it directly gets transit to scene 7.


-----------------------

So now to check that the person has given all the answers correct we will use a check property block.

So if a person answers all the answers correct then he will get a prize and to display it we add another character scene that is scene 8

So we add a give item scene that is scene 9 in which the surprise will be given and then transit to scene 10.

If a person has not given all the answers correcty then he will transit to scene 10 without getting the surprise.



-----------------------

Now we want to add timer to each of the questions so we give 10 seconds to answer each question and display the score after answering each question.


