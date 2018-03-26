# savings-challenge

class SavingChallenge:
    '''A 52 weekly saving challenge that requires one to deposit cash based on a Ksh. 25,50,100 tier.
     works by adding 100 weekly to the original amount. The script stores info '''
    
    start_week = 13  # Its currently week 13 of 52
    start_deposit = 1300 # Week 13 required deposit amount.
    initial_balance = 7800 # account balance before deposit

    def _init_ (self):

        
    def currentWeek(self, week):
        self.week = week
        week == start_week + 1
        return week

    def depositAmount (self, deposit):
        self.deposit = deposit
        deposit = start_deposit + 100 # I choose the 100 Kenya Shilling Tier
        return deposit

    def accountBalance (self,ac_balance):
        self.ac_balance = ac_balance
        ac_balance == initial_balance + deposit
        return ac_balance

# In progress 
    
