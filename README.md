## Budget Breakdown Additional Fields

In Paraguay, a budget line have extra fields that the current budgetBreakdown extension doesn't have and that are relevant for the budget line. 
Those fields are: 
- Estado del CDP: current state of the budget line
- monto comprometido: commited amount to spend in a contracting process
- número de certificado de disponibilidad presupuestaria: availability certificate number, the number of the document that ensures that the money for that contract exists and is available.

## Example
```javascript
"budgetBreakdowns": 
[
    {
        "status": "COMPROMETIDO",
        "availabilityCertificateNumber": 168,
        "commitedAmount": {
            "value": 10.000.000
            "currency": "PYG"
        }
    }
]
```