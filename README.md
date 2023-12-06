# wordsearch
This python function searches for words in a document, with the following criteria:
    Do not include documents where the keyword string shows up only as a part of a larger word. For example, if you were looking for the keyword “closed”, you would not include the string “enclosed.”
    It does not distinguish upper case from lower case letters. So the phrase “Closed the case.” would be included when the keyword is “closed”
    Do not let periods or commas affect what is matched. “It is closed.” would be included when the keyword is “closed”. But you can assume there are no other types of punctuation.

