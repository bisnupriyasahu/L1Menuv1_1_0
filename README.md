#### Instructions for next menu: v1_1_0

-> Start from menu 2023 v1_0_1 in: https://raw.githubusercontent.com/cms-l1-dpg/L1MenuRun3/master/development/L1Menu_Collisions2023_v1_0_1/L1Menu_Collisions2023_v1_0_1.xml 


-> Using the last version of TME and utm grammar, add the following new seeds (for the moment, they can be put at the end of the menu, where there are empty slots):

-> 1 seed for HMT triggers CMSLITDPG-L1_TwoMuShower_
     (it was already integrated by the developers in ~fernanpe/public//for_Elisa/tmp8p2g78xp. , so you can check the logic expression there)

     -> 2 seeds for VBF inclusive CMSLITDPG-L1_DoubleJet_90_L1_DoubleJet80_30_DoubleJet30_Mass_

     -> 4 seeds for VBF exclusive CMSLITDPG-L1_DoubleJet_60_30_L1_DoubleJet40_Mass_Min450_L1_DoubleJet_80_30_L1_DoubleJet_65_30_Mass_Min400_ 

N.B.: there is a bug to be corrected in the VBF exclusive seed, s discussed at the end of its JIRA ticket.