<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

</head>
<body>

    <div>Мазе бот v1 на Вашите услуги</div>

    <script type="text/javascript">

    let visitorFirstname = prompt ("как се казваш - Първо име?");
    let visitorFamilyname = prompt ("Как ти е фамилното име?");
    let visitorAge = prompt ("На колко години си?");
    let visitorGender = prompt ("какъв пол си?");
    
    alert ("Успешна регистрация");

    let isVisitorUnderaged       = visitorAge < 18;
    let isVisitorAnAdult         = visitorAge >= 18;
    let isVisitorGenderMale      = visitorGender == "мъж";
    let isVisitorGenderFemale    = visitorGender == "жена";
    

    if(isVisitorGenderMale&&isVisitorAnAdult)
    {console.log (`Здравейте г-н ${visitorFamilyname}`)};

    if(isVisitorGenderFemale&&isVisitorAnAdult)
    {console.log (`Здравейте г-жо ${visitorFamilyname}`)};

    if(isVisitorGenderMale&&isVisitorUnderaged)
    {console.log (`Здрасти малкия, не пускаме дечица тука - бягай за бира`)};

    if(isVisitorGenderFemale&&isVisitorUnderaged)
    {console.log (`Здрасти малката, не пускаме дечица тука - отивай да си играеш`)};

    alert ("Добре дошъл в мазето на баба," + visitorFirstname + " " + visitorFamilyname +"");
    alert ("Ти си на " + visitorAge + "години");


    let appleWine = "ябълково вино";
    let smokeMeat = "пушено месо";
    let plumJam = "сливов мармалад";
    let marinatedPepper = "мариновани чушки";
    let piggyBank = "прасенце касичка";

    let appleWineQuantity = "10";
    let smokeMeatQuantity = "5"; 
    let plumJamQuantity = "9";
    let marinatedPepperQuantity = "4";
    let piggyBankAmount = "184 лв и 35 стотинки";

    let appleWineSerialNumber = "C7544_10";
    let smokeMeatSerialNumber = "M7441_5";
    let plumJamSerialNumber = "S6491_9";
    let marinatedPepperSerialNumber = "P7485_4";
    let piggyBankSerialNumber = "B6584_184 лв и 35 стотинки";


    alert ("Отчет за продуктите в мазето");

    console.log (`${appleWine} ${appleWineQuantity} ${appleWineSerialNumber}`);
    console.log (`${smokeMeat} ${smokeMeatQuantity} ${smokeMeatSerialNumber}`);
    console.log (`${plumJam}   ${plumJamQuantity}   ${plumJamSerialNumber}`);
    console.log (`${marinatedPepper} ${marinatedPepperQuantity} ${marinatedPepperSerialNumber}`);
    console.log (`${piggyBank} ${piggyBankAmount} ${piggyBankSerialNumber}`);

    let isVisitorYesToDonate = "да, желая да даря";
    let isVisitorNoToDonate = "не, не желая да даря";
    let visitorDonateAmount = "въведете желаната от вас стойност";
    let visitorTotalAmount = 0

    if (isVisitorAnAdult) prompt("желаете ли да дарите пари");

         if (isVisitorNoToDonate) { alert ("ти си куку");
         } else if (isVisitorYesToDonate) { 
            prompt("въведете желаната от вас стойност");
            alert ("сумата за плащане е + visitorDonateAmount + (20% * visitorDonateAmount) ");
         } 

       

    </script>
    </body>
    </html>





                    
                    
                    
