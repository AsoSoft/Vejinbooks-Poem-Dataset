# VejinBooks Poem Dataset
Dataset of 1154 Central Kurdish poems extracted from [vejinbooks.com](http://vejinbooks.com) by AsoSoft group.
This dataset was used for evaluation of an automatic Kurdish poem meter identification method base on Optimality theory 

Prepared By: Aso Mahmudi (`aso.mehmudi[at]gmail.com`)

## Features of all poems:
* Language is Central Kurdish (ckb)
* Meter is specified manually by experts
* Form is specified manually
* non-Kurdish phrases are removed
* Length is more than 5 lines (more than 2 couplets)

## File name convention
Poet + Poem-Number (for example: `Diɫdar002.txt`)

## Text file format
* `title: `  Title of the poem in Kurdish (usually same as the first hemistich of the poem)
* `form: `  Form of the poem in Kurdish (e.g. غەزەل, مەسنەوی, نوێ)
* `meter: `  Meter pattern of the poem in English or Persian (e.g. 10Syllabic, مفاعیلن مفاعیلن مفاعیلن مفاعیلن)
* poem text starts in line 4.
* Number sign (`#`) means the start of a new couplet.
* Non-Kurdish hemistiches are replaced with two plus signs (`++`)
