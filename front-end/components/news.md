<table>
  <tr>
    <th>Views</th>
    <th>Components</th>
    <th>ViewModels</th>
  </tr>
  <tr>
    <td rowspan="2"><img src="../img/newsStatsPos.JPG"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td >Header</td>
    <td >props.header <br>=> positiveStatsHeader</td>
  </tr>
  <tr>
    <td rowspan="1"> Statistics </td>
    <td > [0...*] props.statsGraphs <br>=> postiveStats 
    </td>
  </tr>
  <tr>
    <td rowspan="3"><img src="../img/newsSep.JPG"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td >HeaderNew</td>
    <td> props.header <br>=> HeaderImageNews</td>
  </tr>
  <tr>
    <td rowspan="1"> NewsDescription 
    <td >props.title <br>=> NewsTitle
    <br>props.description <br>=> NewsDescription
    <br>props.handleClick <br>=> detailedNews</td>
  </tr>
  <tr>
    <td rowspan="1"> NewsList 
    <td >props.newsImg <br>=> NewsImageSmall
    <br>props.title <br>=> NewsTitleSmall
    <br>props.description <br>=> NewsDescriptionSmall</td>
  </tr>
  <tr>
    <td rowspan="2"><img src="../img/newsStatsNeg.JPG"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td >Header</td>
    <td >props.header <br>=> negativeStatsHeader</td>
    </tr>
    <tr>
    <td rowspan="1"> Statistics </td>
    <td>[0...*] props.statsGraphsNeg <br>=> negativeStats
    </td>
  </tr>
  
 
  
</table>
