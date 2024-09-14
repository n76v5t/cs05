java c
BCOR 3100 
Homework 1 
August 19, 2024 
Notes: 
• This homework uses an example to help you to think about the systematic risk in banking systems. It is not based on any part of the book or lectures, but is rather a supplement to the lectures on the banking system.
• Please submit electronically on canvas.  You can either write your answers using a text document (e.g.  Microsoft Word), or hand write your answers and scan your pages into pdf (see video instructions on Canvas:  assignments: How to scan hand- written homework); make sure the scanned writing is clear enough for the grader.
• Whenever possible, show the process of your work, not just the answer.  This will help TAs give partial credit.
1. Question 1 (Fragility of the banking system).  The goal of this long-winded question is to help us understand the role of  leverage  and  interconnectedness  in creating system-wide fragility in banking systems.
(a) (2 points) First, consider a single standalone bank.  Suppose it has $10 million in assets and $E million in equity, so the remaining $(10 - E) is debt.  This is done with the following accounting identity:  Asset = Liability + Equity.  Now let’s deﬁne leverage deﬁned as L = 10/E (asset-to-equity ratio).Asset value can change over time.  For instance, if the bank’s operations were more (or less) proﬁtable, its asset value will go up (down).  Suppose the value of the bank’s assets next year has the following probability distribution:Assume that the debt value of the bank does not change.  What happens to the bank when asset value changes?  Well, recall from your accounting class:  if the bank’s asset value goes up (down) by one dollar, its equity value will also go up (down) by one dollar.  Also, the bank goes into bankruptcy if its asset value is equal to or lower than its debt value, which does not change.
Question: what is the probability that this bank will go bankrupt if it has a leverage of 10 to 1 (L = 10)? What if 5 to 1 (L = 5)?
(b)  Now let’s consider what happens to a  network of four banks,  as illustrated in Figure 1.  The arrows represent  exposures  (holding other’s securities).  For instance, bank 2 is exposed to bank 1 (there is an arrow from bank 2 to bank 1), and that means bank 2’s assets contain securities (debt or equity) issued by bank 1.

Figure 1: Network of banks.
Suppose every bank’s balance sheet is of the following form.That is, 80% of bank 2’s assets are securities issued by bank  1, and the re- maining 20% are loans made to other ﬁrms  (non-banks).  This immediately implies that the health of bank 1 impacts bank 2.  If bank  1 goes bankrupt, the securities (debt o代 写BCOR 3100 Homework 1 2024
代做程序编程语言r equity) issued by bank 1 may go down in value, which will lead bank 2 to also sufer a loss in its assets, which may then trigger bank 2 to go bankrupt as well.Recall how investors are paid in bankruptcy:   if a bank goes bankrupt, then its equity becomes worthless, and its debt holders get all remaining asset value with a possible  “haircut” .  For instance, suppose a bank has leverage L = 10 (so equity is  1/L =  1/10 =  10% of total assets).   Suppose the bank’s asset value declines by 30%, so it goes bankrupt, its equity becomes worthless, andits debt is now worth 90%/1−30% = 9/7 as much as before .    So the holders of the bank’s equity sufer a loss of 100% (all lost!), and the holders of its debt sufer a proportional loss of 1 − 9/7 = 9/2 ≈ 22.2%.Suggestion: for all questions below, you don’t need to think in dollar values, but only need to think about values in proportional terms — e.g.  loans are 20% of total asset value, in the balance sheet above.Now that we are done describing background information,  let’s go into the questions.   In  all questions below,  your goal is to ﬁgure out what happens after (only) bank 1 sufers a negative shock: the value of bank 1’s “loans to other ﬁrms” suddenly becomes zero.   (The  “bank-issued securities” on bank 1 balance sheet is not afected, and the  “loans to other ﬁrms” held by other banks are also not afected.) Please answer the questions below.
i. (1 point) How high can the leverage ratio L be so that bank  1 will not go bankrupt in response to this negative shock?
ii. (1.5 points) Now  suppose  banks  hold  debt  securities  issued  by  other banks.  Suppose all banks have a leverage ratio of L = 15.  How many banks will go bankrupt?  Please be speciﬁc in your answer — which banks are bankrupt and why.  Support your answer with calculations.Hint: there could be a  “chain reaction” .  When bank 1 gets the negative shock,  the value of its equity  and its  ability to pay back debt may be afected.   That may impact the asset values of bank 2, because bank 2 holds securities issued by bank  1.  And then that may impacts bank 3, and so on...
iii. (1.5 points) Still assume that L = 15 for all banks.  Now suppose banks hold equity securities issued by other banks. How many of the four banks will go bankrupt?
iv. (1 point) What do you learn from the previous three questions?  Please focus on how inter-bank relationships impact the likelihood of wide-spread bank failures.(There is no  “absolutely correct” answer, even though there are  “better” answers.  You will receive full credit as long as you provide a thoughtful  answer.)





         
加QQ：99515681  WX：codinghelp
