# Expiry return worksheet — Hindi + English

Kaunse batches expiry ke kareeb hain? Free Excel sheet mein list banayein aur supplier ko return dene ke liye slip print karein.

**Download:** GitHub par Excel worksheet file kholein aur **Download raw file** chunein.

Worksheet ke liye signup ya email nahi chahiye. Customer data ki zaroorat nahi. Sample sheet ki 20 rows invented examples hain, kisi real shop ka data nahi.

## Pehle yeh example dekhein

| Pack par likha hai | Sheet mein bharein | Sheet ka calculated result |
|---|---|---|
| EXP 08/2026 | Expiry month: 8; Expiry year: 2026 | Last sellable day: 31 August 2026 |

Yeh expiry calculation ka example hai. Supplier ki return-by date alag field mein khud bharein; sheet supplier ke return terms assume nahi karti.

## Apni return list banayein

1. **Return list - Blank** kholein. Apne batches ke liye 150 empty rows hain.
2. Har batch ki alag row banayein. Medicine, batch number aur expiry month/year pack se bharein.
3. Sheet **Last sellable day**, **Days left** aur **Bucket** calculate karti hai. Expiry ke kareeb batches 0–30, 31–60 aur 61–90 day buckets mein dekhein.
4. Supplier ne jo return-by date di hai, woh bharein. Har supplier ke terms alag ho sakte hain.
5. Action chunein: **Sell first (FEFO)**, **Return to supplier**, **Keep apart - Not for sale**, ya **Other**.

**Supplier slip - print** tab mein return ke saath bhejne wali printable list aur supplier ki receipt ke liye jagah hai.

## Kaunsa batch pehle bechna hai?

FEFO ka matlab: jis batch ki expiry pehle hai, use pehle bechein. Sirf delivery ki date na dekhein—nayi delivery ka batch purane stock se pehle expire ho sakta hai.

## File ke tabs

- **Read this:** Hindi aur English instructions.
- **Return list - Sample:** 20 invented example rows.
- **Return list - Blank:** apne batches bharne ke liye.
- **Supplier slip - print:** return list print karne ke liye.

## Licence

MIT. This is a template, not legal advice.

Related: [Nesayo ka free pharmacy billing software](https://nesayo.com/v/free-pharmacy-billing-software?utm_source=github&utm_medium=readme&utm_campaign=expiry_return_worksheet). Nesayo fits a single medical store that wants billing free forever, in the browser on any phone or computer.
