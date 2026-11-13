[Projects](https://thegipsyjew.github.io/) / [ReviewPluck](https://thegipsyjew.github.io/reviewpluck/) / Reference

Reference

# Amazon review export: the CSV columns explained

By TheGipsyjew · Published and checked on 13 November 2026 · [Editorial method](https://thegipsyjew.github.io/reviewpluck/method/)

The short answer

A ReviewPluck CSV has one review per row and 11 columns: asin, review_id, note (rating), titre (title), texte (text), auteur (author), date, achat_verifie (verified purchase), variante (variant), url_avis (review link) and image_urls. Column names are fixed whatever the interface language, so imports and formulas keep working.
On this page

- [The 11 columns](#section-0)

- [Opening the CSV in Excel without broken accents](#section-1)

- [Useful first formulas](#section-2)

## The 11 columns

The header row keeps the same names in every language of the extension. They come from the original French version of the product.

Columns of the CSV export

| Column | Content

| asin | Amazon product identifier, the same on every row of an extraction

| review_id | Amazon’s identifier of the review, useful to remove duplicates between two extractions

| note | Star rating, 1 to 5

| titre | Review title

| texte | Full review text

| auteur | Reviewer’s public name

| date | Review date

| achat_verifie | Whether Amazon marks it as a verified purchase

| variante | Variant bought (size, colour…) when Amazon shows it

| url_avis | Link to the review on Amazon

| image_urls | Links to the photos attached to the review

## Opening the CSV in Excel without broken accents

Double-clicking a CSV can mangle accents or put everything in one column, depending on your regional settings. Use Data › From Text/CSV in Excel, choose UTF-8 as the file origin and comma as the delimiter. In Google Sheets, File › Import detects both automatically. Pro users can export XLSX directly and skip the import step.

## Useful first formulas

- Average rating: =AVERAGE(C:C) on the note column.

- Share of verified purchases: =COUNTIF(H:H,TRUE)/COUNTA(H:H), adapting the value to what your file contains.

- Reviews mentioning a word: =COUNTIF(E:E,"*battery*") on the texte column.

- Ratings per month: a pivot table with date grouped by month in rows and the average of note in values.

## Try it on your product

[Add ReviewPluck to Chrome](https://chromewebstore.google.com/detail/reviewpluck/bjaoeenljkcnhdffjmffopimkpglkcme) [See features and pricing on reviewpluck.com](https://reviewpluck.com/en/)

## Sources

Official pages checked on 13 November 2026. Plans and limits can change; check them before you choose.

- [ReviewPluck — export preview and features](https://reviewpluck.com/en/#fonctions)

- [Microsoft — Import or export text (.txt or .csv) files](https://support.microsoft.com/en-us/office/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba)
