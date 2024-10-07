# Markdown Files

Whether you write your book's content in Jupyter Notebooks (`.ipynb`) or
in regular markdown files (`.md`), you'll write in the same flavor of markdown
called **MyST Markdown**.
This is a simple file to help you get started and show off some syntax.

## What is MyST?

MyST stands for "Markedly Structured Text". It
is a slight variation on a flavor of markdown called "CommonMark" markdown,
with small syntax extensions to allow you to write **roles** and **directives**
in the Sphinx ecosystem.

For more about MyST, see [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html).

# tujuan

Analisis data memainkan peran krusial dalam pencapaian visi, misi, strategi bisnis, target, dan tujuan bisnis proyek real estate. Visi untuk menciptakan platform yang memberikan manfaat maksimal bagi semua pihak dengan menyediakan prediksi harga rumah yang akurat didukung oleh analisis data yang dapat mengidentifikasi pola dan tren harga berdasarkan faktor-faktor seperti lokasi, ukuran, dan kondisi rumah. Untuk mencapai misi menghasilkan prediksi yang mendekati nilai pasar sebenarnya dan menyediakan alat bantu keputusan yang mudah dipahami, analisis data membantu dalam pemrosesan variabel kunci dan menghasilkan estimasi yang lebih tepat. Strategi bisnis, yang melibatkan penggunaan teknologi machine learning berbasis analisis data, sangat bergantung pada data untuk membangun model prediksi yang akurat. Dengan menganalisis data secara berkelanjutan, performa model dapat dievaluasi dan disempurnakan, misalnya dengan mengukur akurasi menggunakan metrik seperti MAE atau RMSE, untuk mencapai target kesalahan prediksi maksimal 5%. Selain itu, dalam mencapai tujuan bisnis memperkuat transparansi dan kepercayaan dalam transaksi properti, analisis data berperan dalam memberikan informasi yang jelas dan mudah dipahami, yang pada gilirannya meningkatkan transparansi serta membangun kepercayaan di antara para pihak yang terlibat.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
