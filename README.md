Swagger UI generuje nefunkční výchozí JSON, což vede k chybě.
Pro úspěšné odeslání požadavku použijte například tento JSON, nebo jemu podobný:

{
  "customerName": "Testovací zákazník",
  "createdAt": "2025-05-05T10:00:00Z",
  "status": 0,
  "items": [
    {
      "productName": "Testovací produkt 1",
      "quantity": 2,
      "unitPrice": 19.99
    }
  ]
}
