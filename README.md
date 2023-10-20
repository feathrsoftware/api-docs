## Catalan Documentation 🪶

### Retrieve a policy document 📃
If you're looking to retrieve/get a policy document from the api you'll have to make a request with the url below, followed by the unique id of the policy or plan number. For example you would make a request by replacing `{policy_id}` with `3a3e1508-59d5-445a-8623-953e085be885` and requesting the url which will respond with the raw json data. You must be authorized to make these requests.

Request URL: `http://api.quillsure.com/api/v1/policy/{policy_id}`

> Response:
```json
{
  "id": "3a3e1508-59d5-445a-8623-953e085be885",
  "number": "QS-0064329",
  "accepted_by": "587621f3-8e13-41e6-9b4e-12564f528641",
  "accepted_date": 1697819624,
  "renewal_date": 1697819658,
  "excess": 15.0,
  "notes": [
    {
      "id": "3f0c6980-a6fa-4683-ba05-a54ac2d5b43c",
      "content": "Hello 👋🏼, this is the content of the note!",
      "added_by": "587621f3-8e13-41e6-9b4e-12564f528641",
      "added_at": 1697819658
    }
  ],
  "appliance": {
    "id": "b8dabafc-6e42-46ce-81e7-ec8ff3cc48d1",
    "manufacturer": "Apple",
    "model_number": "A2681",
    "serial_number": null,
    "guarantee": 365,
    "purchase_price": 1099,
    "purchase_date": 1697819879,
    "breakdown_start_date": 1697820175,
    "good_working_order": true,
    "type": "Laptop"
  },
  "source": "quillsure",
  "status": "Live"
}
```
