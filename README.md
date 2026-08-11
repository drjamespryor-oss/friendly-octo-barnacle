# friendly-octo-barnacle
IF:     DIA >= Roll_Trigger AND New_Strike > Current_Strike AND New_Expiration > Current_Expiration AND (New_Call_Bid - Old_Call_Ask) >= Minimum_Net_Credit  THEN:     BUY TO CLOSE Old Calls     SELL TO OPEN Higher-Strike Calls     RECORD Net Credit     Maintain 100,000-Share Coverage ELSE:     HOLD / REASSESS
