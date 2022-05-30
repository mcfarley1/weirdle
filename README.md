# weirdle
A variation of Wordle using Excel that can be adapted to specific scenarios.

Weirdle operates similarly to "Wordle", and also has a new word come into play once per day.  Words range from 4 to 6 letters, and can be customized to suit a particular audience.  Weirdle has a tab called "Words" in which the word list appears in column B and the dates they will be active appear in column A.  A user can customize this word list, adding as many words as they desire, and set the dates for when each word will be in play.  To prevent errors, if the current date is not included in the date range, the first date will automatically reset to the current date, and all subsequent dates will be adjusted accordingly with one day intervals.  Once the list is customized, the "Words" tab should be hidden if you desire to prevent cheating.  There is also a fake keyboard on the right that will change color according to correct or incorrect choice and placement of letters.  The instructions are included in the spreadsheet, and are as follows:

1.	The length of the word is represented by the number of gray boxes.
2.	Enter your guess in cell B8, then press the "Play" button.
3.	Letters that are correct and in the correct location will appear green.
4.	Letters that are correct but are in the wrong location will appear amber.
5.	Letters that are incorrect will remain black, and will be shaded dark gray in the fake keyboard on the right.
6.	You get ten attempts.
