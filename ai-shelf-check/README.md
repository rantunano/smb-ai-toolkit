# 🛒 AI Shelf Check
*¿La IA puede leer tu tienda?*

**Live tool:** https://rantunano.github.io/smb-ai-toolkit/ai-shelf-check/

More shoppers ask an AI assistant before they buy. This free tool checks whether **one product page** is easy to read — for AI assistants and for people — and gives you:

- 🎯 A **10-point score** with fixes, most urgent first
- 🧩 **schema.org `Product` structured data (JSON-LD)** ready to paste, including price, availability, shipping and returns
- 💬 Optional **`FAQPage`** markup from your top customer questions
- 📋 A **plain-text product card** for your description, marketplaces or saved WhatsApp reply
- 🖨️ A printable summary

*Revisa una página de producto en 3 minutos: puntaje de 10, arreglos, datos estructurados listos para pegar y una ficha en texto plano.*

Runs 100% in your browser. Nothing is sent anywhere. No sign-up. *Todo se queda en tu navegador.*

## The 10 checks · *Las 10 revisiones*

| | Check | *Revisión* |
|---|---|---|
| 🏷️ | Product name says what it is | *El nombre dice qué es* |
| 💲 | Price is readable text, not an image | *El precio es texto* |
| 📦 | Stock status is written | *La existencia está escrita* |
| 🚚 | Shipping cost and time on the product page | *Envío en la página* |
| ↩️ | Returns policy in plain words | *Devoluciones claras* |
| 📝 | Description with real specs (60+ words) | *Descripción con datos* |
| 💬 | 3–5 top customer questions answered | *Preguntas frecuentes* |
| 🖼️ | Images have alt text | *Texto alternativo* |
| ⭐ | Customer reviews are visible | *Reseñas visibles* |
| 🧩 | Structured product data | *Datos estructurados* |

🚫 **Blocker:** if people must log in or message you to see the price, nothing outside your chat can read it.

♿ Everything that makes a page readable for a machine also helps people who use screen readers.

## Important · *Importante*

- Structured data helps machines understand your page. It **does not guarantee** that any AI assistant or search engine will show or recommend your product.
- Many store platforms already generate `Product` markup. Test your page first so you don't publish it twice: [Google Rich Results Test](https://search.google.com/test/rich-results) · [Schema Markup Validator](https://validator.schema.org/).
- Only mark up reviews and FAQs that are **visible on the page**.

## Sources · *Fuentes*

### Data
1. **Adobe** — "U.S. Holiday Shopping Season to Hit Record $275.1 Billion Online, Rising 6.7% YoY", press release, Sep 28, 2026. AI traffic to U.S. retail sites forecast +130% YoY (Nov 1–Dec 31, 2026), measured as shoppers clicking a link; based on Adobe Analytics (1+ trillion visits, 100M SKUs). https://news.adobe.com/news/2026/09/adobe-us-holiday-shopping-season-to-hit-record
2. **Salesforce** — "2026 Holiday Predictions", Caila Schwartz, Jul 20, 2026. 20% of 2026 holiday e-commerce traffic forecast to come from AI chat agents; 50% of shoppers use an AI assistant in their buying journey. Methodology not published on the page. https://www.salesforce.com/blog/holiday-retail-predictions-2026/
3. **Adyen Retail Report 2026** — Mexico: 42% of shoppers used AI assistants when buying; 48% would let AI handle the whole purchase, payment included. As reported by Mexico Business News, Mar 5, 2026 (sample and fieldwork not published). https://mexicobusiness.news/ecommerce/news/ai-drives-42-shopper-decisions-mexico · Adyen: https://www.adyen.com/es_MX/index-reports/retail/index-nrf-ch2
4. **Expansión** — "Buen Fin 2026: el 48% de los mexicanos dejaría que una IA compre por ellos", Jimena Fuentes, Nov 4, 2026. Reports Adyen (47% prioritize clarity on returns when delegating to AI) and TrendValue's exploratory *AI Shelf Report* (~1,280 answers from 8 AI tools, Oct 17–20, 2026: for phones, 71% of cited sources were media, reviews and comparison sites; 9% stores). https://expansion.mx/tecnologia/2026/11/04/buen-fin-2026-mexicanos-dejarian-que-una-ia-compre-por-ellos

### How-to references
- schema.org: [Product](https://schema.org/Product), [Offer](https://schema.org/Offer), [MerchantReturnPolicy](https://schema.org/MerchantReturnPolicy), [OfferShippingDetails](https://schema.org/OfferShippingDetails)
- Google Search Central: [Product structured data](https://developers.google.com/search/docs/appearance/structured-data/product), [FAQ structured data](https://developers.google.com/search/docs/appearance/structured-data/faqpage)
- W3C WAI: [Images tutorial (alt text)](https://www.w3.org/WAI/tutorials/images/)

## Related tools
- [AI Depth Ladder](../ai-depth-ladder/) — is AI in your tabs or in your processes?
- [AI Readiness Check](../ai-readiness-check/) — 10 questions, 5 pillars

---
Part of the free [SMB AI Toolkit](https://rantunano.github.io/smb-ai-toolkit/) · MIT License · Made by Rodrigo — feedback welcome via [GitHub Discussions](https://github.com/rantunano/smb-ai-toolkit/discussions).
