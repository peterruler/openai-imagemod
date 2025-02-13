# Beschreibung

- ChatGPT Dall-E Shirt Replacement via generative KI - Machen Sie ChatGPT zu einer Generative-Fill Bild-KI
- Basierend auf dem Projekt von [Jeff Heaton](https://github.com/jeffheaton/app_generative_ai)

## OpenAI API-Schlüssel abrufen

- Besuchen Sie die [OpenAI Plattform](https://platform.openai.com/settings/organization/billing/overview), um Ihren API-Schlüssel zu erhalten.

## Demo (Jupyter Notebook)

- Sie können das Jupyter Notebook auf [Google Colab](https://colab.research.google.com/) ausführen.

## Screenshot

![ChatGPT Shirt Replacement](portfolio-12.png?raw=true "ChatGPT Shirt Replacement")

![ChatGPT Shirt Replacement](hero-image.png?raw=true "ChatGPT Shirt Replacement")


## Hinweise

- Verwenden Sie ein Tool wie z.B. GIMP, um Teile des Bildes zu löschen, die Sie ersetzen möchten, und ein zweites Bild mit dem vollständigen Bild.
```
  image_url_1 = "https://peterstroessler.com/src/images/hero/hero-image.png"
  image_url_2 = "/content/drive/My Drive/jeff_heaton/hero-image-free.png" # mit ausradierten, zu füllenden Bereichen

  # Load the images from URLs
  image_1 = load_image_from_url(image_url_1)  # laden von internetadresse
  image_2 = load_image_from_url2(image_url_2) # laden aus google drive Datei
  # kann individuell getauscht, etc. werden
  ```

## OpenAI API-Schlüssel in Google Colab hinterlegen

Um Ihren OpenAI API-Schlüssel sicher in Google Colab zu hinterlegen, folgen Sie diesen Schritten:

1. Öffnen Sie Ihr Jupyter Notebook auf [Google Colab](https://colab.research.google.com/).
2. Tragen Sie Ihren OpenAI API-Schlüssel manuell in den Google Colab Passwort-Save in der linken Spalte auf der Google Colab Oberfläche mit dem Schlüssel-Icon ein, um den API-Schlüssel sicher zu speichern. Wählen Sie als Bezeichnung z.B. `OPENAI_API_KEY` und fügen Sie den kopierten OpenAI API-Schlüssel aus den [OpenAI API-Schlüsseln](https://platform.openai.com/settings/organization/api-keys) ein.
