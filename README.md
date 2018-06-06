# 12 Fun CSS Text Shadows
Como a maioria dos efeitos CSS, as sombras de texto são extremamente simples de implementar em uma forma básica, mas podem assumir uma variedade de formas diferentes se você realmente empregar algum trabalho nelas. Usando vírgulas como separador, você pode empilhar sombras de CSS umas sobre as outras para aumentar drasticamente a intensidade e o realismo do efeito. Veja alguns exemplos:

## The Basic Shadow
	text-shadow:  2px  4px  3px  rgba(0,0,0,0.3);

## Quick and Dirty Letterpress
    body  {
	    background:  #222;
    }

    #text h1 {
	    color:  rgba(0,0,0,0.6);
	    text-shadow:  2px  2px  3px  rgba(255,255,255,0.1);
    }

## Hard Shadow
	text-shadow:  6px  6px  0px  rgba(0,0,0,0.2);

## Double Shadow
	text-shadow:  4px  3px  0px  #fff, 9px 8px 0px rgba(0,0,0,0.15);

## Down and Distant
    text-shadow:	0px  3px  0px  #b2a98f,
				    0px  14px  10px  rgba(0,0,0,0.15),
				    0px  24px  2px  rgba(0,0,0,0.1),
				    0px  34px  30px  rgba(0,0,0,0.1);

## Close and Heavy
    text-shadow:	0px  4px  3px  rgba(0,0,0,0.4),
				    0px  8px  13px  rgba(0,0,0,0.1),
				    0px  18px  23px  rgba(0,0,0,0.1);

## Seriously 3D Text
    text-shadow:	0 1px 0 #ccc,
					0 2px 0 #c9c9c9,
					0 3px 0 #bbb,
					0 4px 0 #b9b9b9,
					0 5px 0 #aaa,
					0 6px 1px rgba(0,0,0,.1),
					0 0 5px rgba(0,0,0,.1),
					0 1px 3px rgba(0,0,0,.3),
					0 3px 5px rgba(0,0,0,.2),
					0 5px 10px rgba(0,0,0,.25),
					0 10px 10px rgba(0,0,0,.2),
					0 20px 20px rgba(0,0,0,.15);

## True Inset Text
    background-color: #666666;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    background-clip: text;
    color: transparent;
    text-shadow: rgba(255,255,255,0.5) 0px 3px 3px;

## Glowing
    text-shadow: 0px 0px 6px rgba(255,255,255,0.7);

## Superhero
    text-shadow:	-10px 10px 0px #00e6e6,
				    -20px 20px 0px #01cccc,
					-30px 30px 0px #00bdbd;

## Multiple Light Sources
    text-shadow:	0px 15px 5px rgba(0,0,0,0.1),
				    10px 20px 5px rgba(0,0,0,0.05),
					-10px 20px 5px rgba(0,0,0,0.05);

## Soft Emboss
    color: rgba(0,0,0,0.6);
    text-shadow:	2px 8px 6px rgba(0,0,0,0.2),
                    0px -5px 35px rgba(255,255,255,0.3);
