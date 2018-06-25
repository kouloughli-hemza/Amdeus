# Amdeus
Amadeus API
Laravel Version 5 and Above

##Install with Composer

composer require AmadeusNonymous/Amadeus:dev-master

Provider Class

put on your config/app.php in provider array this class

  AmadeusNonymous\Amadeus\AmadeusProvider::class,
 

#Aliases add this in aliases array

'Amadeus' => AmadeusNonymous\Amadeus\Amadeus::class,

#publish with composer run this command php artisan vendor:publish

now you can check this file amadeus.php on config path

#usage

 /*
  $data = [
   'origin'=>'BER',
   'destination'=>'LON',
   'departure_date'=>'2017-08-25',
   'return_date'=>'2017-08-28',
   'arrive_by'=>'2017-08-25T16:00',
   'return_by'=>'2017-08-28T16:00',
   'adults'=>'1',
   'children'=>'1',
   'infants'=>'0',
   'include_airlines'=>'',
   'exclude_airlines'=>'',
   'nonstop'=>'false',
   'one-way'=>'false',
   'duration'=>1,
   'max_price'=>980,
   'currency'=>'USD',
   'travel_class'=>'ECONOMY',
   'number_of_results'=>'ECONOMY',
  ];

  $flights = Amadeus::make($data,'flights/low-fare-search');
 */
