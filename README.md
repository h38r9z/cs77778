java c
Assignment 
FIN   6126
Suppose you are a hedge fund manager. Your intern   finds that   sorting   individual   stock’s trailing 12-month returns (i.e.,   12-month cumulative stock returns) and hold the portfolio for the next   three months makes great money in US, which is the main result in the   seminal paper by Jagadeesh and Titman   (1993).
You are skeptical about the application   in China.   So,   you   would   like to test the usefulness   of   (12,3)-momentum strategy in China.
You first download a sample of   Chinese A-share   stocks,   excluding those   with   ST/ST*   and   firms   in the financial industry. Then you define the momentum trading   signal   as
cum   returni,t−11→t      =   (1 + returni,t−11) × (1 + returni,t−10) × ⋯ × (1 + returni,t   ) −   1 
where   returni,t      is   stock’s   monthly   return, and   cum   returni,t−11→t is   the   12-month   cumulative return   (which   includes   current   month).
After   you   calculate   the   momentum   trading   signal, cum   returni,t−11→t, in   each   month,   you   rank all firms accordingly. You calculate the average   excess returns   in   the   top   30%   and bottom   30% extreme portfolios with three-month holding   period.

where p represents   the   extreme   po代 写FIN 6126 AssignmentPython
代做程序编程语言rtfolios, and return is   the   average   portfolio   returns.   Lastly, you   generate   the   time   series   of   long-short   portfolio   returns.
returnLS,t+1    = return3,t+1→t+3    − return1,t+1→t+3
(Note that due to the limitation of   Excel, we select   a   subsample of   20   stocks with balanced panel. Thus, the top 30% portfolio contains the top 6 stocks and the bottom   30% portfolio   contains the bottom 6   stocks.)
Questions
1.       In the attached   Excel   spreadsheet,   please   generate   a   time   series   of   returns   in the LS   portfolio.
2.       Calculate the annual   average returns,   standard   deviation   of   returns,   and   the   Sharpe   ratio   of   the   LS   portfolio   returns.
3.       Please calculate the   annual   CAPM   alpha   and the   annual FF4   alpha   (using MKTRF,   SMB,   HML, and MOM), as well   as the   CAPM beta.
4.       Assume that your initial wealth is   $100 in   all   three   portfolios   (Top   30%,   Bottom   30%,
and LS). Please draw the time series graph   of   the   cumulative NAV   in the   sample period.
5.       What is your   conclusion   about the   effectiveness   of   momentum   strategy   in   China?







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
