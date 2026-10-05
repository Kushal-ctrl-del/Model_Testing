>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null).
...
>>> MESSAGE: Hi this is Priya, order #NC1042 hasn't arrived yet, it's been 9 days
```json
{
  "customer_name": "Priya",
  "order_id": "NC1042",
  "issue_type": "delay",
  "amount_inr": null
}
```

total duration:       7.4905559s
load duration:        5.7907ms
prompt eval count:    115 token(s)
prompt eval cached:   24 token(s)
prompt eval duration: 3.167875s
prompt eval rate:     28.73 tokens/s
eval count:           44 token(s)
eval duration:        4.304792s
eval rate:            10.22 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null).
...
... MESSAGE: Ravi here. Got my coffee pack broken, order NC2210, paid Rs 849
```json
{
  "customer_name": "Ravi",
  "order_id": "NC2210",
  "issue_type": "damaged",
  "amount_inr": 849
}
```

total duration:       5.9077282s
load duration:        6.0442ms
prompt eval count:    114 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.087102s
prompt eval rate:     25.76 tokens/s
eval count:           48 token(s)
eval duration:        4.806117s
eval rate:            9.99 tokens/s
>>> /clear
Cleared session context
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null).
...
... MESSAGE: Want refund for NC3051 - Anjali Menon. I paid Rs 1,299
```json
{
  "customer_name": "Anjali Menon",
  "order_id": "NC3051",
  "issue_type": "refund",
  "amount_inr": 1299
}
```

total duration:       6.1606159s
load duration:        7.0435ms
prompt eval count:    115 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.145345s
prompt eval rate:     25.32 tokens/s
eval count:           51 token(s)
eval duration:        4.999368s
eval rate:            10.20 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null).
...
... MESSAGE: Order NC4120 wrong item delivered. Thanks, Karthik
```json
{
  "customer_name": "Karthik",
  "order_id": "NC4120",
  "issue_type": "wrong_item",
  "amount_inr": null
}
```

total duration:       5.3429428s
load duration:        5.373ms
prompt eval count:    106 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 818.227ms
prompt eval rate:     24.44 tokens/s
eval count:           46 token(s)
eval duration:        4.511935s
eval rate:            10.20 tokens/s
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE : Sneha: how do I change my
... address? no order id yet
```json
{
  "customer_name": "Sneha",
  "order_id": null,
  "issue_type": "other",
  "amount_inr": null
}
```

total duration:       7.2002115s
load duration:        12.4916ms
prompt eval count:    237 token(s)
prompt eval cached:   151 token(s)
prompt eval duration: 3.133513s
prompt eval rate:     27.45 tokens/s
eval count:           40 token(s)
eval duration:        4.042865s
eval rate:            9.89 tokens/s
>>> /CLEAR
Unknown command '/CLEAR'. Type /? for help
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE : Sneha: how do I change my
... address? no order id yet
```json
{
  "customer_name": "Sneha",
  "order_id": null,
  "issue_type": "other",
  "amount_inr": null
}
```

total duration:       4.7978076s
load duration:        6.348ms
prompt eval count:    105 token(s)
prompt eval cached:   83 token(s)
prompt eval duration: 903.697ms
prompt eval rate:     24.34 tokens/s
eval count:           40 token(s)
eval duration:        3.874496s
eval rate:            10.32 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE : Mohammed Irfan here. NC55
... 33 is delayed, I want my money back, Rs 450
```json
{
  "customer_name": "SMohammed Irfan",
  "order_id": "NC5533",
  "issue_type": "refund",
  "amount_inr": 450
}
```

total duration:       6.1347176s
load duration:        6.8197ms
prompt eval count:    118 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.131297s
prompt eval rate:     28.29 tokens/s
eval count:           51 token(s)
eval duration:        4.989462s
eval rate:            10.22 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE : Mohammed Irfan here. NC553
... 3 is delayed, I want my money back, Rs 450
```json
{
  "customer_name": "Mohammed Irfan",
  "order_id": "NC5533",
  "issue_type": "refund",
  "amount_inr": 450
}
```

total duration:       6.0627009s
load duration:        6.6382ms
prompt eval count:    116 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.176055s
prompt eval rate:     25.51 tokens/s
eval count:           50 token(s)
eval duration:        4.869727s
eval rate:            10.27 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE: URGENT!!! nc6001 packet lea
... king. -Deepa S. (Rs 1,050 order)
```json
{
  "customer_name": "Deepa S.",
  "order_id": "NC6001",
  "issue_type": "damaged",
  "amount_inr": 1050
}
```

total duration:       6.1407025s
load duration:        5.0347ms
prompt eval count:    118 token(s)
prompt eval cached:   85 token(s)
prompt eval duration: 1.250221s
prompt eval rate:     26.40 tokens/s
eval count:           50 token(s)
eval duration:        4.878126s
eval rate:            10.25 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE : Hello, Suresh. Order numb
... er is NC7788. Late by 3 days. Paid 2,499 rupees
```json
{
  "customer_name": "Suresh",
  "order_id": "NC7788",
  "issue_type": "delay",
  "amount_inr": 2499
}
```

total duration:       6.1971339s
load duration:        6.3994ms
prompt eval count:    122 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.367883s
prompt eval rate:     26.32 tokens/s
eval count:           49 token(s)
eval duration:        4.815323s
eval rate:            10.18 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE: Anna, NC8890 innum varala,
...  12 days aachu. - Vignesh
```json
{
  "customer_name": "Anna",
  "order_id": "NC8890",
  "issue_type": "delay",
  "amount_inr": 12
}
```

total duration:       5.5357813s
load duration:        6.1976ms
prompt eval count:    115 token(s)
prompt eval cached:   86 token(s)
prompt eval duration: 1.133425s
prompt eval rate:     25.59 tokens/s
eval count:           45 token(s)
eval duration:        4.388739s
eval rate:            10.25 tokens/s
>>> /clear
Cleared session context
>>> Extract the fields from the customer message. Return ONLY valid JSON, no extra text, with keys: customer_name (string), order_id (string, upperc
... ase, or null), issue_type (one of: delay, damaged, refund, wrong_item, other), amount_inr (number or null). MESSAGE: Just wanted to say the cof
... fee was great! - Lakshmi
...
```json
{
  "customer_name": "Lakshmi",
  "order_id": null,
  "issue_type": "other",
  "amount_inr": null
}
```

total duration:       4.8008881s
load duration:        6.3241ms
prompt eval count:    106 token(s)
prompt eval cached:   87 token(s)
prompt eval duration: 814.026ms
prompt eval rate:     23.34 tokens/s
eval count:           41 token(s)
eval duration:        3.973s
eval rate:            10.32 tokens/s
>>> Send a message (/? for help)