# PhP_primogiorno

<?php
    // Esercizio 2

    $intero = 12;
    $float = 123.45;
    $string = 'mi stringa';
    $boolean = true;

    echo $intero. "<br>";
    echo $float. "<br>";
    echo $string. "<br>";
    echo $boolean. "<br>";

    if ($boolean){
        echo 'la variabile è true'. "<br>";
    }  else { 
        echo 'la variabile è false'. "<br>";
    }

    //Esercizio 3

    const NUM_INTERO = 12;
    echo NUM_INTERO;
    echo "<br>";
    // Esercizio 4

    $text1 = "Marco"; 
    $text2 = "hai"; 
    $text3 = "sete"; 
    $text4 = "?";
    $text5 = "Perchè";
    $text6 = '$text2';
    $text7 = 'bevuto';
    $text8 = "tutto";

    $frase = $text1.' '.$text2.' '.$text3.$text4.' '.$text5.' '.$text2.' '.$text7.' '.$text8;
    echo $frase;

    //Esercizio 5

    $words1 = [
  'una',
  67,
  'vita',
  'colle',
  'mi',
  'rosso',
  [
    'oscura',
    'era',
    89,        
    [
      'mezzo',
      [
        'cammin',
        'Nel',
        [
          'selva',
          'la',
          [
            'via',
            'una',
            true,
          ]
        ],
      ]
    ],
    'ritrovai',
    'per'
  ],
'diritta'
];

$words2 = [
  'elemento1' => 25.89,
  'elemento2' => 'nostra', 
   'elemento3' => [
      'Virgilio',
      'smarrita',
      'ché'
    ]
];
//$vuoto= "<br>";
//$results = $words2('elemento1') //<--- Tutto in questa variabile
//var_dump ($results);
//echo $results[2];
var_dump($words2);
$results = $words2;
var_dump($results);




//Spiegazione

<?php
/*

//Declaracion de variable

$prova = "Patricia";
$prova1 = 'patricia';
$frase =  "$prova";
$frase = '$prova';


$frase1 = 'mi chiamo $prova';

$frase2 = 'mi chiamo $prova1';
$frase3 = "mi chiamo $prova";
$frase4 = "mi chiamo $prova1";
echo $frase1. "\n";
echo $frase2. "\n";
echo $frase3. "\n";
echo $frase4. "\n";
$names = ['luis', 'carlos', 'mauro'];
print_r($names). "\n";
var_dump($names). "\n";
*/

$persons = [
    'name' => 'francesco',
     'name' => 'Juan',
      'name' => 'Pedro',
];
array_push($persons, 'hola');
array_pop($persons);
print_r($persons['name']);
var_dump($persons);
