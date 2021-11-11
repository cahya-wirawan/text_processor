# Text Processor

Text Normalisation or Inverse Normalisation for Indonesian, e.g. 
- "123 kg" -> "seratus dua puluh tiga kilogram" 
- "Harga notebook itu $250 atau sekitar Rp 3,000,000" -> "Harga notebook itu dua ratus lima puluh dollar atau sekitar tiga juta rupiah"

## Usage
```
from text_processor import TextProcessor

tp = TextProcessor()
print(tp.normalize("123 kg"))
```