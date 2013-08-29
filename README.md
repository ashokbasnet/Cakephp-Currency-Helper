Cakephp-Currency-Helper
=======================

### CakePHP-CurrencyHelper

For Cakephp 2.0 and above

This is a cakephp helper which can be used to format currencies of differnt countries. The currency formatter can format some unique currencies Format like Nepali and Indian Currencies too.

Copy the helper to the Views/Helpers.

Include it in the Controller or View as required.

For including in a controller,

After class declartion,


public $helpers = array('Currency');


For including in a view,


$this->Helpers->load('Currency');



Some examples

$this->Currency->formatCurrency(1000045.25);             //1,000,045.25 (USD)         


$this->Currency->formatCurrency(1000045.25, "CHF");      //1'000'045.25 


$this->Currency->formatCurrency(1000045.25, "EUR");      //1.000.045,25 


$this->Currency->formatCurrency(1000045, "JPY");         //1,000,045 


$this->Currency->formatCurrency(1000045, "LBP");         //1 000 045 


$this->Currency->formatCurrency(1000045.25, "NPR");      //10,00,045.25 


$this->Currency->formatCurrency(1000045.25, "INR");      //10,00,045.25 

The supported currencies are :-

ARS  //  Argentine Peso  
AMD  //  Armenian Dram  
AWG  //  Aruban Guilder  
AUD  //  Australian Dollar  
BSD  //  Bahamian Dollar  
BHD  //  Bahraini Dinar  
BDT  //  Bangladesh, Taka  
BZD  //  Belize Dollar  
BMD  //  Bermudian Dollar  
BOB  //  Bolivia, Boliviano  
BAM  //  Bosnia and Herzegovina, Convertible Marks  
BWP  //  Botswana, Pula  
BRL  //  Brazilian Real  
BND  //  Brunei Dollar  
CAD  //  Canadian Dollar  
KYD  //  Cayman Islands Dollar  
CLP  //  Chilean Peso  
CNY  //  China Yuan Renminbi  
COP  //  Colombian Peso  
CRC  //  Costa Rican Colon  
HRK  //  Croatian Kuna  
CUC  //  Cuban Convertible Peso  
CUP  //  Cuban Peso  
CYP  //  Cyprus Pound  
CZK  //  Czech Koruna  
DKK  //  Danish Krone  
DOP  //  Dominican Peso  
XCD  //  East Caribbean Dollar  
EGP  //  Egyptian Pound  
SVC  //  El Salvador Colon  
ATS  //  Euro  
BEF  //  Euro  
DEM  //  Euro  
EEK  //  Euro  
ESP  //  Euro  
EUR  //  Euro  
FIM  //  Euro  
FRF  //  Euro  
GRD  //  Euro  
IEP  //  Euro  
ITL  //  Euro  
LUF  //  Euro  
NLG  //  Euro  
PTE  //  Euro  
GHC  //  Ghana, Cedi  
GIP  //  Gibraltar Pound  
GTQ  //  Guatemala, Quetzal  
HNL  //  Honduras, Lempira  
HKD  //  Hong Kong Dollar  
HUF   //  Hungary, Forint  
ISK   //  Iceland Krona  
INR  //  Indian Rupee  
IDR  //  Indonesia, Rupiah  
IRR  //  Iranian Rial  
JMD  //  Jamaican Dollar  
JPY  //  Japan, Yen  
JOD  //  Jordanian Dinar  
KES  //  Kenyan Shilling  
KWD  //  Kuwaiti Dinar  
LVL  //  Latvian Lats  
LBP  //  Lebanese Pound  
LTL  //  Lithuanian Litas  
MKD  //  Macedonia, Denar  
MYR  //  Malaysian Ringgit  
MTL  //  Maltese Lira  
MUR  //  Mauritius Rupee  
MXN  //  Mexican Peso  
MZM  //  Mozambique Metical  
NPR  //  Nepalese Rupee  
ANG  //  Netherlands Antillian Guilder  
ILS  //  New Israeli Shekel  
TRY  //  New Turkish Lira  
NZD  //  New Zealand Dollar  
NOK  //  Norwegian Krone  
PKR  //  Pakistan Rupee  
PEN  //  Peru, Nuevo Sol  
UYU  //  Peso Uruguayo  
PHP  //  Philippine Peso  
PLN  //  Poland, Zloty  
GBP  //  Pound Sterling  
OMR  //  Rial Omani  
RON  //  Romania, New Leu  
ROL  //  Romania, Old Leu  
RUB  //  Russian Ruble  
SAR  //  Saudi Riyal  
SGD  //  Singapore Dollar  
SKK  //  Slovak Koruna  
SIT  //  Slovenia, Tolar  
ZAR  //  South Africa, Rand  
KRW  //  South Korea, Won  
SZL  //  Swaziland, Lilangeni  
SEK  //  Swedish Krona  
CHF  //  Swiss Franc   
TZS  //  Tanzanian Shilling  
THB  //  Thailand, Baht  
TOP  //  Tonga, Paanga  
AED  //  UAE Dirham  
UAH  //  Ukraine, Hryvnia  
USD  //  US Dollar  
VUV  //  Vanuatu, Vatu  
VEF  //  Venezuela Bolivares Fuertes  
VEB  //  Venezuela, Bolivar  
VND  //  Viet Nam, Dong  
ZWD  //  Zimbabwe Dollar  