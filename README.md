# Creating-Multiple-Choices-Questions-and-Answers-System
Create a Multiple Choices Questions and Answers System with fully functional Scoring feature ( Viết chương trình hỗ trợ làm ngân hàng câu hỏi trắc nghiệm )

How it works:
1. Start by generate your question with 'generateQuestions'.

  a. It will ask if this the first time you generate questions. Answer with y/n.
  
  b. Input number of desirable questions.
  
  c. Input your questions follow by answers. Complete a question with a 'Done' input.
  
  d. Input the question's correct answer.
  
Ex: QUESTION 1: --Your question here--

    Answer: --Your answer here-- (remember to put in a) b) c) or d) before each answer)
    
    Answer: ...
    
    Answer: Done
    
    Correct Answer: --Your correct answer here-- (You can either retype, copy or just put in A) B) C) or D) )
    
->Your questions will be put in 'questions.txt'. This is your databank.

2. It will automatically generate a compact list of your input questions to 'compact.txt' for easy handling (like getting the number of questions in the databank)
3. You can try taking the test with 'answer'
4. the code will put your input answers to 'answers.txt'
5. the code get the correct answers from 'questions.txt, put them in 'correctAnswer.txt', compare them with your answers in 'answers.txt' and print out your result
