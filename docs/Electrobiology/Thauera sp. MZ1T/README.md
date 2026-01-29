

{% with pdf_file = "sigs.2696029.pdf" %}

## Example: Embedding a PDF file

<object data="{{ pdf_file }}" type="application/pdf" style="width:100%; height:800px;">
    <embed src="{{ pdf_file }}" type="application/pdf" />
</object>

{% endwith %}