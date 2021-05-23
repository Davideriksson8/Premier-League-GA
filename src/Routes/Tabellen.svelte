<script>
    import Link from 'svelte-routing/src/Link.svelte';
</script>




<li class="tabell">
    
<table class="tabell">
<tr>
<td class="lag">Lag:</td>		<td>S</td> <td>V</td>	<td>O</td>	<td>F</td> <td>GD</td> <td>P</td>
</tr>
<tr>
<td class="lag"><Link to="/Mancity"><p>Man City</p></Link></td> <td>38</td><td>27</td><td>5</td><td>6</td><td>51</td><td>86</td>
</tr>

<tr>
<td class="lag"><Link to="/Manutd"><p>Man Utd</p></Link></td><td>38</td><td>21</td><td>11</td><td>6</td><td>29</td><td>74</td>
</tr>

<tr>
<td class="lag"><Link to="/Liverpool"><p>Liverpool</p></Link></td> <td>38</td> <td>20</td> <td>9</td><td>9</td><td>26</td><td>69</td>
</tr>

<tr>
<td class="lag">Chelsea</td><td>38</td><td>19</td><td>10</td><td>9</td><td>22</td><td>67</td>
</tr>

<tr>
<td class="lag">Leicester City</td><td>38</td><td>20</td><td>6</td><td>12</td><td>18</td><td>66</td>
</tr>

<tr>
<td class="lag">West Ham</td><td>38</td><td>19</td><td>8</td><td>11</td><td>15</td><td>65</td>
</tr>

<tr>
<td class="lag">Tottenham</td><td>38</td><td>18</td><td>8</td><td>12</td><td>23</td><td>62</td>
</tr>

<tr>
<td class="lag">Arsenal</td><td>38</td><td>18</td><td>7</td><td>13</td><td>16</td><td>61</td>
</tr>

<tr>
<td class="lag">Leeds Utd</td><td>38</td><td>18</td><td>5</td><td>15</td><td>8</td><td>59</td>
</tr>

<tr>
<td class="lag">Everton</td><td>38</td><td>17</td><td>8</td><td>13</td><td>-1</td><td>59</td>
</tr>

<tr>
<td class="lag">Aston Villa</td><td>38</td><td>16</td><td>7</td><td>15</td><td>9</td><td>55</td>
</tr>

<tr>
<td class="lag">Newcastle</td><td>38</td><td>12</td><td>9</td><td>17</td><td>-16</td><td>45</td>
</tr>

<tr>
<td class="lag">Wolves</td><td>38</td><td>12</td><td>9</td><td>17</td><td>-16</td><td>45</td>
</tr>

<tr>
<td class="lag">Crystal Palace</td><td>38</td><td>12</td><td>8</td><td>18</td><td>-25</td><td>44</td>
</tr>

<tr>
<td class="lag">Southampton </td><td>38</td><td>12</td><td>7</td><td>19</td><td>-21</td><td>43</td>
</tr>

<tr>
<td class="lag">Brighton</td><td>38</td><td>9</td><td>14</td><td>15</td><td>-6</td><td>41</td>
</tr>

<tr>
<td class="lag">Burnley</td><td>38</td><td>10</td><td>9</td><td>19</td><td>-22</td><td>39</td>
</tr>

<tr>
<td class="lag">Fulham</td><td>38</td><td>5</td><td>13</td><td>20</td><td>-26</td><td>28</td>
</tr>

<tr>
<td class="lag">West Brom</td><td>38</td><td>5</td><td>11</td><td>22</td><td>-41</td><td>26</td>
</tr>

<tr>
<td class="lag">Sheffield Utd</td><td>38</td><td>7</td><td>2</td><td>29</td><td>-43</td><td>23</td>
</tr>




</table>	
</li>


<style>

* {
    font-size: 17px;
    color: white;
}

td {
    padding: 0 7px;
    border-right: solid 1px white;
    border-bottom: solid 1px white;
    text-align: center;
}

td.lag {
    text-align: unset;
}


li.tabell {
    justify-self: center;
}

tr:nth-child(odd) {
    background-color: #37003c;

} 

tr:nth-child(even) {
    background-color: #9123bd;
}

table.tabell {
    
    
    color: white;
}







</style>