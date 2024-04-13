This is a .h header file that defines a series of templates :


// *********************************************************

//                  estructures_bàsiques.h

// *********************************************************

//
//  (c)2024 Albert Gonzàlez i García. Prohibit l'ús sense
//  permís exprés per escrit de l'autor.
//
//  Aquest fitxer defineix els prototips de diverses estructures
//  utilitzades habitualment en programes escrits en C.
//  Per fer-les servir s'han de declarar primer els tipus
//  a una capçalera o a un .c de manera adient, per exemple :
//
//  DEFINEIX_FIFO(int);
//
//  Després, a fitxer de codi ( .c )  s'han de definir les funcions
//  i les variables, per xemple :
//
//  CODI_FIFO(int);
//
//  CREA_FIFO(int,el_meu_fifo_de_sencers);
//
//  Amb això hem creat una fifo per a sencers anomenada el_meu_fifo_de_sencers
//  Ara s'ha d'incialitzar amb ( per a 1220 elements):
//
//       el_meu_fifo_de_sencers.creador(1220);
//
