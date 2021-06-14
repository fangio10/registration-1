# registration

In this repo, pool operators may register to be a member of the Cardano Renewable Energy Stake Pool Alliance.

By submitting a pull request you agree that all the submited information will be publicly available to everyone.

Also, by submitting you affirm that your pool is powered by a renewable energy source.

Simply create a pull request after adding the information of your pool in the registry.json file

Registration JSON Example:

{
 "ticker": "GOALS",                                                       # Mandatory
 "poolId": "pool1nh9j5qucsddxkzn3m4dm4gxkhwtpya4wm4e0ye2u0puaqgkcm65",  # Mandatory
 "social": {                                                            # At least 1 Mandatory more optional
   "twitter": "adaGOALS",
   "facebook": " ",  
   "instagram": " ",
   "youtube": " "
 },
 "telegram": "ADA_GOALS_Stake_Pool",                                             # Mandatory Personal Telegram Handle
 "operatorName": " ",                                   # Optional
 "github": " "                                                     # Optional
}
