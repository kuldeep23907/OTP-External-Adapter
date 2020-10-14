# Chainlink OTP External Adapter

## Input Params

member: Ethereum Address/Name of the OTP receiver
to: Mobile no. of the OTP receiver
amount: No of token involved in the transaction
otp: OTP to be sent
action:  The action which is being performed with the tokens (eg. MINTED, BURNED)

## Output (returns true if OTP has been sent to the user)
{
   "jobRunID":"0",
   "data":{
     `"msid":true,
      "result":1
   },
   "result":1,
   "statusCode":200
}
