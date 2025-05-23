# 🧾 Hukuk Asistanı – Türkçe Dilekçe Üretim Modeli

Bu proje, Türkçe hukuki dilekçeler üretmek üzere **MT5-small** modeli kullanılarak geliştirilmiş bir yapay zeka tabanlı hukuk asistanıdır. Model, kullanıcıdan alınan kısa açıklamalara dayanarak resmi dilekçe metinleri üretmektedir.

## 🎯 Proje Amacı

Gerçek dilekçe örneklerinden oluşturduğum özel veri seti ile **MT5-small modeli fine-tune edildi**. Amaç, kullanıcıların hukuki ihtiyaçlarını doğal dilde ifade ederek otomatik dilekçeler üretebilecekleri bir sistem oluşturmaktır.

## 🛠️ Kullanılan Teknolojiler

- 🤖 HuggingFace Transformers (MT5-small)
- 🧠 Google Colab – Model eğitimi
- 📊 TensorBoard – Eğitim metrikleri izleme
- 🗂️ Özel veri seti – Gerçek dilekçelerden hazırlanmış

## 📈 Eğitim Süreci

Model eğitimi sırasında modelin kayıp değerleri TensorBoard üzerinden takip edilmiştir:

![Tensorboard eğitim sonucu grafiksel veriler](tensorboard%20grafiksel%20metrikler.png)

## 🔍 Özellikler

- Doğal dilden resmi dilekçe metni üretimi
- Türkçe dilinde özelleştirilmiş model
- Hukuki metinlere uygun dil ve yapı

## 📄 Kullanım

> Detaylı kullanım için `MT5_SMALL.ipynb` dosyasını inceleyin.

Notebook içerisinde:
- Veri seti hazırlama
- Model eğitimi
- Çıktı üretme adımları yer almaktadır.

## 📬 Katkıda Bulun

Katkı sağlamak isterseniz pull request gönderebilir veya issue açabilirsiniz.

---
