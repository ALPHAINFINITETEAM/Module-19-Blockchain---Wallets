# Module-19-Blockchain---Wallets
crypto_wallet/Krypto_jobs

In this assignment, i will be buiding a new disruptive platform (Kryptojobs2go).KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable  customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

###  Step 1: Import Ethereum Transaction Functions into the KryptoJobs2Go Application
I will use two python files 'Krypto_jobs.py' and 'crypto_wallet.py'.

'Krypto_jobs.py' file contains the code associated with the web interface of the application. The code included in this file is compatible with the Streamlit library. I will write all of the codes for this Challenge in this file

'crypto_wallet.py' file contains the Ethereum transaction functions that i have created throughout this module’s lessons. By using import statements, i will integrate the `crypto_wallet.py` Python script into the KryptoJobs2Go interface program that is found in the `krypto_jobs.py` file.

### Step 2: Sign and Execute a Payment Transaction
Next, I will write the code that will calculate a fintech professional’s wage, in ether, based on the worker’s hourly rate and the number of hours that they work for a customer. (The fintech professionals’ hourly rates are provided in the `candidate_database` that is found in `krypto_jobs.py`.)

### Step 3: Inspect the Transaction
Now it's time to put it all together and test the KryptoJobs2Go application with my newly integrated Ethereum wallet. I will send a test transaction by using the application’s web interface, and then look up the resulting transaction in Ganache
