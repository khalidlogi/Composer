# Composer

## Installation
Official installation method is via composer and its packagist package mpdf/mpdf.

$ composer require mpdf/mpdf

## Usage
The simplest usage (since version 7.0) of the library would be as follows:

<?php

require_once __DIR__ . '/vendor/autoload.php';

$mpdf = new \Mpdf\Mpdf();
$mpdf->WriteHTML('<h1>Hello world!</h1>');
$mpdf->Output();
