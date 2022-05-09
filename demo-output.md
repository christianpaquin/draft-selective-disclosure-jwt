# Creating the JWS-SD
Contents of the JWS-SD:
```
{
    "iss": "https://example.com/issuer",
    "sub_jwk": {
        "kty": "RSA",
        "n": "s6DP6K0K9umbF1xrurtCS6vZlg4AXgBsYXBFrr8ICpOASEedD4aih_PcAYUoSsxyx0fPtg6gnhfqdz82VH134xyp_AQRmZs2h9ep4U4tI10qNLQEih0py3aTZO5SccZwefoawkkuPtz0FPoIh6rofEZTrA0Jmop7pbFPp1sdC6jCaHyRdn8YepUo-erT1VXuF8SrBLEhdt1GzKUYw15vwuzaPNPLWqcUWloJ3B7vB6rjlrmRYxzOsy5UR5PozHDGXIEQE_eKmty01X9KoF5bpe8cJEtTThVBXc3k8lwpMurO7VZjK7esdTsTUS09xmGhk54A_D33GO1p9stMbFkcAQ",
        "e": "AQAB"
    },
    "iat": 1516239022,
    "exp": 1516247022,
    "sd_claims": {
        "given_name": "O/I6emucqsLviMjcbo+vWYHHeQW3uSXEu8xwkeZOf+Y=",
        "family_name": "Ziy4w2d/8h/L8TZdzvXVgOKjnHF7RS5ZvkRz34B6JFA=",
        "email": "puE5pGVwxLAzuOOxGPCVjQf7lUg8PE/dsSWRvSHGni4=",
        "phone_number": "Om1c8N9H4WZqcqESdgaj1ge6PKX7PIxCqEN8FRneOxA=",
        "address": "nksvf9mv8zqP2g/eIQK0385DWnmsI7+UhIGhHYw18tk=",
        "birthdate": "a4UjSYF+KpCUveaC3pa4CfnXRhi+e5kE72pHIUZiiNQ="
    }
}
```


The serialized JWS-SD:
```
eyJhbGciOiAiUlMyNTYifQ.eyJpc3MiOiAiaHR0cHM6Ly9leGFtcGxlLmNvbS9pc3N1ZXIiLCAic3ViX2p3ayI6IHsia3R5IjogIlJTQSIsICJuIjogInM2RFA2SzBLOXVtYkYxeHJ1cnRDUzZ2WmxnNEFYZ0JzWVhCRnJyOElDcE9BU0VlZEQ0YWloX1BjQVlVb1NzeHl4MGZQdGc2Z25oZnFkejgyVkgxMzR4eXBfQVFSbVpzMmg5ZXA0VTR0STEwcU5MUUVpaDBweTNhVFpPNVNjY1p3ZWZvYXdra3VQdHowRlBvSWg2cm9mRVpUckEwSm1vcDdwYkZQcDFzZEM2akNhSHlSZG44WWVwVW8tZXJUMVZYdUY4U3JCTEVoZHQxR3pLVVl3MTV2d3V6YVBOUExXcWNVV2xvSjNCN3ZCNnJqbHJtUll4ek9zeTVVUjVQb3pIREdYSUVRRV9lS210eTAxWDlLb0Y1YnBlOGNKRXRUVGhWQlhjM2s4bHdwTXVyTzdWWmpLN2VzZFRzVFVTMDl4bUdoazU0QV9EMzNHTzFwOXN0TWJGa2NBUSIsICJlIjogIkFRQUIifSwgImlhdCI6IDE1MTYyMzkwMjIsICJleHAiOiAxNTE2MjQ3MDIyLCAic2RfY2xhaW1zIjogeyJnaXZlbl9uYW1lIjogIk8vSTZlbXVjcXNMdmlNamNibyt2V1lISGVRVzN1U1hFdTh4d2tlWk9mK1k9IiwgImZhbWlseV9uYW1lIjogIlppeTR3MmQvOGgvTDhUWmR6dlhWZ09Lam5IRjdSUzVadmtSejM0QjZKRkE9IiwgImVtYWlsIjogInB1RTVwR1Z3eExBenVPT3hHUENWalFmN2xVZzhQRS9kc1NXUnZTSEduaTQ9IiwgInBob25lX251bWJlciI6ICJPbTFjOE45SDRXWnFjcUVTZGdhajFnZTZQS1g3UEl4Q3FFTjhGUm5lT3hBPSIsICJhZGRyZXNzIjogIm5rc3ZmOW12OHpxUDJnL2VJUUswMzg1RFdubXNJNytVaElHaEhZdzE4dGs9IiwgImJpcnRoZGF0ZSI6ICJhNFVqU1lGK0twQ1V2ZWFDM3BhNENmblhSaGkrZTVrRTcycEhJVVppaU5RPSJ9fQ.sALNjFDCWsclLJ99f4LJx9oTj3rSQncipMmM3N0fUtFMOgM6gQ3W423q1E8mreDF_YlsFx3fBka285yAcr5XpgQknuSdkSDjCq2pX33o2zgLRfy4Tm01nvTnLPr8riXKfW-NT_iZ18nzv7w3wTL-QIiFZ76wMJlshO1rfbOfGQmdY9hr5Zcg-MDCTwB2z146Wf5XSCR2KCDd7wQ0R01wQcXvNJNKuAnpj1KOW6fSU-uAe5fFj4NY2CRy257V86TwQxZX1DCkzJEIDbF01aW2bb8Y04NxKIYPHGCn4AzZQqy8g2HDmGv2nHt3W8LUjTktvnwvl4uOvYgv0G_9B_YICg
```


# Creating the JWS-SD-Proof
Contents of the JWS-SD-Proof:
```
{
    "nonce": 757482,
    "sd": {
        "family_name": "[\"HCxQejkPbmldEKsnfw5GcQ==\", \"Doe\"]",
        "address": "[\"whuqJTrb+lVSPs8zMLIJDg==\", {\"street_address\": \"123 Main St\", \"locality\": \"Anytown\", \"region\": \"Anystate\", \"country\": \"US\"}]"
    }
}
```


The serialized JWS-SD-Proof:
```
eyJhbGciOiAiUlMyNTYifQ.eyJub25jZSI6IDc1NzQ4MiwgInNkIjogeyJmYW1pbHlfbmFtZSI6ICJbXCJIQ3hRZWprUGJtbGRFS3NuZnc1R2NRPT1cIiwgXCJEb2VcIl0iLCAiYWRkcmVzcyI6ICJbXCJ3aHVxSlRyYitsVlNQczh6TUxJSkRnPT1cIiwge1wic3RyZWV0X2FkZHJlc3NcIjogXCIxMjMgTWFpbiBTdFwiLCBcImxvY2FsaXR5XCI6IFwiQW55dG93blwiLCBcInJlZ2lvblwiOiBcIkFueXN0YXRlXCIsIFwiY291bnRyeVwiOiBcIlVTXCJ9XSJ9fQ.t6ZdkWY4R4d711wKzL3wmRau6oSWLqdvWr6v6IBNa6no4YSXwV9bxUjH7zMovk0dTIaGemMk5NGfJ6gTWCFhgRXuTF5H5JPLkHq9SWcqBfMf_CbSdx4OfjI7YTW-Z4HV8M7JpcAQ4gJ8qGW26ou5eEBLfw2XjsiA6X2OU8mAQ7kop4-xiEAjeOSnC_1C00D049RpuTIV8GqByOzDiNXS6WR_JlQeQa-S7pK4yGQkNpCDFkR4lP4-406lqrYUhvMRKDVusWRdRS3HLnf2de30ZyoZYsJsG3pM-yKGFIphV9i8jyNmI7stJQZdQ2x2-4XS2B-PC-Q_RSww_ynQOITZgA
```


# Creating the Combined Representation
Combined Representation:
```
eyJhbGciOiAiUlMyNTYifQ.eyJpc3MiOiAiaHR0cHM6Ly9leGFtcGxlLmNvbS9pc3N1ZXIiLCAic3ViX2p3ayI6IHsia3R5IjogIlJTQSIsICJuIjogInM2RFA2SzBLOXVtYkYxeHJ1cnRDUzZ2WmxnNEFYZ0JzWVhCRnJyOElDcE9BU0VlZEQ0YWloX1BjQVlVb1NzeHl4MGZQdGc2Z25oZnFkejgyVkgxMzR4eXBfQVFSbVpzMmg5ZXA0VTR0STEwcU5MUUVpaDBweTNhVFpPNVNjY1p3ZWZvYXdra3VQdHowRlBvSWg2cm9mRVpUckEwSm1vcDdwYkZQcDFzZEM2akNhSHlSZG44WWVwVW8tZXJUMVZYdUY4U3JCTEVoZHQxR3pLVVl3MTV2d3V6YVBOUExXcWNVV2xvSjNCN3ZCNnJqbHJtUll4ek9zeTVVUjVQb3pIREdYSUVRRV9lS210eTAxWDlLb0Y1YnBlOGNKRXRUVGhWQlhjM2s4bHdwTXVyTzdWWmpLN2VzZFRzVFVTMDl4bUdoazU0QV9EMzNHTzFwOXN0TWJGa2NBUSIsICJlIjogIkFRQUIifSwgImlhdCI6IDE1MTYyMzkwMjIsICJleHAiOiAxNTE2MjQ3MDIyLCAic2RfY2xhaW1zIjogeyJnaXZlbl9uYW1lIjogIk8vSTZlbXVjcXNMdmlNamNibyt2V1lISGVRVzN1U1hFdTh4d2tlWk9mK1k9IiwgImZhbWlseV9uYW1lIjogIlppeTR3MmQvOGgvTDhUWmR6dlhWZ09Lam5IRjdSUzVadmtSejM0QjZKRkE9IiwgImVtYWlsIjogInB1RTVwR1Z3eExBenVPT3hHUENWalFmN2xVZzhQRS9kc1NXUnZTSEduaTQ9IiwgInBob25lX251bWJlciI6ICJPbTFjOE45SDRXWnFjcUVTZGdhajFnZTZQS1g3UEl4Q3FFTjhGUm5lT3hBPSIsICJhZGRyZXNzIjogIm5rc3ZmOW12OHpxUDJnL2VJUUswMzg1RFdubXNJNytVaElHaEhZdzE4dGs9IiwgImJpcnRoZGF0ZSI6ICJhNFVqU1lGK0twQ1V2ZWFDM3BhNENmblhSaGkrZTVrRTcycEhJVVppaU5RPSJ9fQ.sALNjFDCWsclLJ99f4LJx9oTj3rSQncipMmM3N0fUtFMOgM6gQ3W423q1E8mreDF_YlsFx3fBka285yAcr5XpgQknuSdkSDjCq2pX33o2zgLRfy4Tm01nvTnLPr8riXKfW-NT_iZ18nzv7w3wTL-QIiFZ76wMJlshO1rfbOfGQmdY9hr5Zcg-MDCTwB2z146Wf5XSCR2KCDd7wQ0R01wQcXvNJNKuAnpj1KOW6fSU-uAe5fFj4NY2CRy257V86TwQxZX1DCkzJEIDbF01aW2bb8Y04NxKIYPHGCn4AzZQqy8g2HDmGv2nHt3W8LUjTktvnwvl4uOvYgv0G_9B_YICg.eyJhbGciOiAiUlMyNTYifQ.eyJub25jZSI6IDc1NzQ4MiwgInNkIjogeyJmYW1pbHlfbmFtZSI6ICJbXCJIQ3hRZWprUGJtbGRFS3NuZnc1R2NRPT1cIiwgXCJEb2VcIl0iLCAiYWRkcmVzcyI6ICJbXCJ3aHVxSlRyYitsVlNQczh6TUxJSkRnPT1cIiwge1wic3RyZWV0X2FkZHJlc3NcIjogXCIxMjMgTWFpbiBTdFwiLCBcImxvY2FsaXR5XCI6IFwiQW55dG93blwiLCBcInJlZ2lvblwiOiBcIkFueXN0YXRlXCIsIFwiY291bnRyeVwiOiBcIlVTXCJ9XSJ9fQ.t6ZdkWY4R4d711wKzL3wmRau6oSWLqdvWr6v6IBNa6no4YSXwV9bxUjH7zMovk0dTIaGemMk5NGfJ6gTWCFhgRXuTF5H5JPLkHq9SWcqBfMf_CbSdx4OfjI7YTW-Z4HV8M7JpcAQ4gJ8qGW26ou5eEBLfw2XjsiA6X2OU8mAQ7kop4-xiEAjeOSnC_1C00D049RpuTIV8GqByOzDiNXS6WR_JlQeQa-S7pK4yGQkNpCDFkR4lP4-406lqrYUhvMRKDVusWRdRS3HLnf2de30ZyoZYsJsG3pM-yKGFIphV9i8jyNmI7stJQZdQ2x2-4XS2B-PC-Q_RSww_ynQOITZgA
```

