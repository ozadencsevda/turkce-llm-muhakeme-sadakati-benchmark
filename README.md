# Turkish LLM Reasoning Faithfulness Benchmark - Sample Dataset

Bu veri seti, Türkçe muhakeme görevlerinde LLM'lerin faithfulness ve epistemik kalibrasyonunu değerlendirmek için oluşturulmuştur.

## Veri Seti Yapısı

| Sütun | Açıklama |
|-------|----------|
| `question_id` | Benzersiz soru kimliği |
| `category` | Muhakeme kategorisi |
| `difficulty` | Zorluk seviyesi (easy, medium, hard) |
| `context` | Sorunun bağlamı |
| `question` | Soru metni |
| `gold_evidence` | Doğru cevap için gerekli kanıt |
| `gold_answer` | Doğru cevap |

## Kategoriler

- **numerical_reasoning**: Sayısal hesaplama ve matematiksel çıkarım
- **temporal_reasoning**: Zaman ilişkileri ve sıralama
- **compositional_reasoning**: Çok adımlı bilgi birleştirme
- **logical_inference**: Mantıksal çıkarım ve tümdengelim
- **causal_reasoning**: Neden-sonuç ilişkileri
- **analogical_reasoning**: Benzerlik ve örüntü eşleştirme

## İstatistikler

- **Toplam soru**: 18 (örnek set)
- **Kategori başına**: 3 soru (her zorluk seviyesinden birer tane)
- **Tam veri seti**: 489 soru
