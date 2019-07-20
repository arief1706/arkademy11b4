   
   
<html>
<head>
<title>JSON testing - Arkademy</title>
<script type='text/javascript'>
    var JSON_text = {
                        name:'Mohammad Arief Rahman',
                        umur:26,
                        status_nikah:true,
                        hobi:['coding','gaming','trading']
                   };
                    
    var nikah;
     
    if(JSON_text.status_nikah){
        nikah = "Single";
    }else{
        nikah = "Married";
    }
     
    document.write ("Name = "+JSON_text.name +"<br> Age = "+JSON_text.umur+"<br> Hobbies = "+JSON_text.hobi[2]+ "<br> Married = "+nikah);
    
    var JSON_txt = { list:[
                        
                                {school:'Taman Madya 1', universitas:'IPS'}
                        ]
                   };
                    
    
     
    document.write("<br> List School : <br />");
    document.write("<ol>")
    for(var i=0; i<JSON_txt.list.length; i++){
        document.write("<li>" + JSON_txt.list[i].school + ",  Departement " + JSON_txt.list[i].universitas + "</li>");
    }
    document.write("</ol>")
    
    var inter;
     
    if(JSON_text.status_inters){
        inters = "No";
    }else{
        inters = "Yeah, I'am Intersted </br>";
    }
     
    document.write ( "<br> Interest Coding = "+inters);
    
    //------//
    
    
     var JSON_text = {
                        
                        skill:['Beginner','Advance','Expert']
                   };
    document.write ("</br>Skill = "+JSON_text.skill[0]);
    
	
     
</script>
</head>
<body>