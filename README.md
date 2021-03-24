# card_transactions_SOA

# Requirements for application

    1.App should operate by four entyties:
        -Card
        -Client
        -Transactions
        -Account
**Card** has a number, expier date, client ID, type of payment system.
        It can be opened, closed, connected to the uniq account, operate with transactions (put/get money), get any info related
        to it (owner name,  account number, type of payment system etc)

**Client** has id, name, surname, account ID, also gives a possibility to operate
by name, surname,account ID etc.

**Transactions** has id, date, account ID, card ID, amount. Also it is possible 
to get all data for it

**Account** has account id, client id, transactions id, card id. Also it is possible
to get or set info for it.

