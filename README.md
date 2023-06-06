# FlashCards

I used the Java Swing library to create a flash card study application that allows the user to create flash card decks and review them to help prepare for upcoming test.

The QuizCardBuilder opens a JFrame with a Question JTextField and Answer JTextField the inputs are made and the user selects the next card JButton which stores the created card on an ArrayList<QuizCards> and clears out the JTextFields for the next inputs. Once the user has created the appropriate number of cards for the deck they can select the save from the file menu. Which saves the current card to the deck and the user can select where to save the file and what to name it. That calls the saveFile(File file) method which utilizes a try catch block to write the contents of each card into the selected file. 

The QuizCardPlayer allows the user to select a created deck from the QuizCardBuilder that reads each line of text from the file and and transfers those lines into cards using the QuizCards class and storing them onto an ArrayList<>. Then the cards are displayed in a JFrame with the question and the user can select the nextCard function wich uses the isShowAnswer flag to check if the answer needs to be displayed or if the next card in the card deck should be displayed. Once the application reaches the end of the card deck the message "That was the last card" will be displayed.
  
Upload instructions (using Java 18):
  1. download the java classes to your computer
  2. open your command line and navigate to the folder containing the java classes
  3. compile the QuizCardBuilder.java: javac QuizCardBuilder.java
  4. then run java QuizCardBuilder
  5. Create your card deck and save
  6. compile and run the QuizCardPlayer.java 
  7. navigate to the file that has the created deck and open the file
  8. enjoy your created deck.

  
# Credits
  This project comes from **Head First Java, 3rd edition** By Kathy Sierra, Bert Bates, Trisha Gee
