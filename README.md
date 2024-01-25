# Asset-Hexa-Server
## APIs
- API: [https://asset-hexa-server.vercel.app](https://asset-hexa-server.vercel.app)
- Post API for account: [https://asset-hexa-server.vercel.app/accounts](https://asset-hexa-server.vercel.app/accounts)
- Get API for account. Example:
```
https://asset-hexa-server.vercel.app/accounts?email=front@example.com
```

- Post INCOME API for transections: [https://asset-hexa-server.vercel.app/transections?type=INCOME](https://asset-hexa-server.vercel.app/transections?type=INCOME)
- Post EXPENSE API for transections: [https://asset-hexa-server.vercel.app/transections?type=EXPENSE](https://asset-hexa-server.vercel.app/transections?type=EXPENSE)

- Get API for transections: [https://asset-hexa-server.vercel.app/transections](https://asset-hexa-server.vercel.app/transections)
- Example: [https://asset-hexa-server.vercel.app/transections?type=INCOME&email=backend@example.com](https://asset-hexa-server.vercel.app/transections?type=INCOME&email=backend@example.com)

## Object Example For Post INCOME API for transections
```
[
    {
        "date": "",
        "account": "Cash",
        "type": "INCOME",
        "category": "Salary",
        "amount": 5000,
        "Notes": "First Income"
    },
    {
        "account": "Cash",
        "type": "EXPENSE",
        "category": "Food",
        "amount": 2000,
        "Notes": "First Income"
    },
    {
        "account": "Cash",
        "type": "TRANSFER",
        "to": "Bkash",
        "amount": 2000,
        "Notes": "First Income"
    }
]
```
- API For PI chart separated by categorys https://asset-hexa-server.vercel.app/catPi?type=EXPENSE&email=backend@example.com
- Example
```
https://asset-hexa-server.vercel.app/catPi?type=EXPENSE&email=backend@example.com
```
