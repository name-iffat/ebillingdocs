# Currency Wallet

## How To Change The Currency Wallet

1. Open `lib/modules/tera_wallet/helpers/currency_text_input_formatter.dart` file in project
2. Change the symbol to 'RM' or any relevant currency symbol.

```flutter
class CurrencyTextFormatter extends TextInputFormatter {
  final f = NumberFormat.currency(
      locale: kAdvanceConfig['DefaultLanguage'],
      name: '',
      symbol: 'RM',
      decimalDigits: 0);
```

![Wallet Top-up](/ebillingdocs/img/wallet-currency.png)
