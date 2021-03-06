Thanks for looking into this project!

Here are a couple things to make your contribution top-notch:
 - Make sure your JSON is compliant to RFC 4627
   - (Consider running it through [this validator](https://jsonformatter.curiousconcept.com/))
   - Use 4-space tabs
 - Break down pieces by color/suit if values are similar
   - (A deck of all aces would make for some confusing games)
 - If the board doesn't change/break down, including a simple "board" entry is sufficient
   - ex: Chess - the board never changes
   - ex: Settlers of Catan does **not** fit this specification
 - Have `name`,`edition`, and `publisher` as separate attributes
 
 Nit-pick polishing:
  - Specify if a dice is more/less than 6 sides
  - Use `dice` attribute to denote all dice; `die` and `dices` should be avoided
   
   
