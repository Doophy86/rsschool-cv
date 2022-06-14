1. **Dmitrii Sedov**
2. **Tel** *+7-961-307-69-69* **Discord** - Doophy (@doophy86)
3. I used to do programming, then worked as the head of the IT department for a long time. Now I have decided to resume such a process as programming, because I want to work at home. I chose js front/end because it is very popular and allows me to develop many interesting applications.
4. I was already familiar with JS earlier, but superficially. I wrote CRM for a real estate agency using HTML, CSS, PHP and a little JS. JS used for jquery and ajax functions.
5. **Sample code**
<?php
>if ($view['Doj_id'] == 12 or $view['user_id'] == 10198)
>    {   $ico4 = "<a href='#' onClick='del_zap(".$fmyo1['id_kassa']."); return false;'><img src='../dir/img/del.png' width='20' height='20'></a>";
>	     $edit_k = 'class="edit '.$fmyo1['id_kassa'].'"';
>	}else
>    {
>	$ico4 = '';
>	$edit_k = '';
>	}
?>
>function del_zap(id_kassa)
>{
>	if (confirm('Record will be delete. Confirm?')) 
>	{
>	$("#"+id_kassa).remove(); //Hide from Screen
>
>	//del record
>	$.ajax({
>		    type: "POST",
>		    url: "del_kassa_script.php",
>		    data: {id_kassa:id_kassa},
>		    success: function(data)
>		    {
>		    alert(data);
>           }
>		  });
>	} //end modal window (confirm)
>};

7. Education - higher. Faculty of Applied Mathematics in Economics
8. English - Reading. Now I'm pulling up hard.