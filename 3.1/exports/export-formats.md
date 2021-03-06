# Export formats

By default, the export format is determined by the extension of the file. If you want 
to explicitly configure the export format, you can pass it through as 2nd parameter. 

## XLSX

```php
(new InvoicesExport)->download('invoices.xlsx', \Maatwebsite\Excel\Excel::XLSX);
```

## CSV

```php
(new InvoicesExport)->download('invoices.csv', \Maatwebsite\Excel\Excel::CSV);
```

## TSV

```php
(new InvoicesExport)->download('invoices.tsv', \Maatwebsite\Excel\Excel::TSV);
```

## ODS

```php
(new InvoicesExport)->download('invoices.ods', \Maatwebsite\Excel\Excel::ODS);
```

## XLS

```php
(new InvoicesExport)->download('invoices.xls', \Maatwebsite\Excel\Excel::XLS);
```

## HTML

```php
(new InvoicesExport)->download('invoices.html', \Maatwebsite\Excel\Excel::HTML);
```

::: warning Exporting to PDF
If you'd like to export to PDF, you must now install a PDF rendering library yourself. Please refer to the [PhpSpreadsheet Documentation](https://phpspreadsheet.readthedocs.io/en/develop/topics/reading-and-writing-to-file/#pdf) for more information.
:::

## MPDF

```php
(new InvoicesExport)->download('invoices.pdf', \Maatwebsite\Excel\Excel::MPDF);
```

## DOMPDF

```php
(new InvoicesExport)->download('invoices.pdf', \Maatwebsite\Excel\Excel::DOMPDF);
```

## TCPDF

```php
(new InvoicesExport)->download('invoices.pdf', \Maatwebsite\Excel\Excel::TCPDF);
```
