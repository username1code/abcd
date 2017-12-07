# abcd first commit
 $cars=array(
                array("volvo", 22,18),
                array ("bmw",24,19),
                array("mercedes",12,20),
                array("saab",34,23)
            );
                    for($row =0;$row<4;$row++){
                print "<p><b>row number $row</b></p>";
                print "<ul>";
                for($col=0;$col<3;$col++){
                    print "<li>".$cars[$row][$col]."</li>";
                    print"</ul>";
                }
                    }
