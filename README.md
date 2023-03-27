# dvocifren
dvocifren

<?php

function broj_cifara($broj){
    return strlen($broj);
}
$niz=[3,4,67,65,33,223,767];
function saberi_br($n,$niz){
    $zbir=0;
    for($i=0;$i<count($niz);$i++){
        if(broj_cifara($niz[$i])==$n)
        $zbir+=$niz[$i];
    }
    return $zbir;
}
echo  saberi_br(3,$niz);
