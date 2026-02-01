
{% with pdf_file = "kjeldsen-et-al-2019-on-the-evolution-and-physiology-of-cable-bacteria.pdf" %}

## Example: Embedding a PDF file

<object data="{{ pdf_file }}" type="application/pdf" style="width:100%; height:800px;">
    <embed src="{{ pdf_file }}" type="application/pdf" />
</object>

{% endwith %}



{% with pdf_file = "rsos.231991.pdf" %}

## Example: Embedding a PDF file

<object data="{{ pdf_file }}" type="application/pdf" style="width:100%; height:800px;">
    <embed src="{{ pdf_file }}" type="application/pdf" />
</object>

{% endwith %} 