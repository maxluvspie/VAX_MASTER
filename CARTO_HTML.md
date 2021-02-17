##--------------------------INFO WINDOW--------------------------##
<div class="cartodb-popup dark v2">
  <a href="#close" class="cartodb-popup-close-button close">x</a>
  <div class="cartodb-popup-content-wrapper">
    <div class="cartodb-popup-content"style="min-height:300px;">
      <h2 style="width:100%; text-align:center;text-transform:capitalize;letter-spacing:.2px;">{{borough}} — {{neighborhoods}}</h2>
        <hr style="width:90%; margin:auto; margin-bottom:8px;margin-top:8px;height: 1px;">
        <div class="row" style="margin-bottom:20px">
            <div class="column" style="float: left; width: 33%;text-align: center;">
                <h4>Est. Adult<br>Population</h4>
                <p>{{pop_estimate}}</p>
            </div>
            <div class="column" style="float: left; width: 33%;text-align: center;">
                <h4>Household<br>Median Income</h4>
                <p>&#36;{{household_median_income}}</p>
            </div>
            <div class="column" style="float: right; width: 33%;text-align: center;">
                <h4>Citywide<br>Median Income</h4>
                <p>&#36;63998</p>
            </div>            
        </div>
        <hr style="width:90%; margin:auto; margin-bottom:8px;height: 1px;">
        <div class="row" style="margin-bottom:50px">
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Fully<br>Vaccinated</h4>
                <p>{{perc_fully}}%</p>
            </div>
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Partially<br>Vaccinated</h4>
                <p>{{perc_partially}}%</p>
            </div>
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Citywide<br>Average</h4>
                <p>4.58%</p>
            </div>
        </div>
        <hr style="width:90%; margin:auto; margin-bottom:8px;height: 1px;">
        <div class="row" style="margin-bottom:50px">
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Poverty Rate</h4>
                <p>{{poverty_rate}}%</p>
              </div>
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Insured</h4>
                <p>{{percent_insured}}%</p>
            </div>
            <div class="column" style="float: left; width: 33%; text-align: center;">
                <h4>Uninsured</h4>
                <p>{{percent_uninsured}}%</p>
            </div>
        </div>
        <div style="width:100%; text-indent: 60%">
            <p style="font-size:12px;margin-bottom: -5px;">City of New York [<a href="https://public.tableau.com/views/COVID-19VaccinationTracker/Geography?:language=en&:display_count=y&:origin=viz_share_link" target="_blank">1</a>]</p>
            <p style="font-size:12px">U.S. Census Bureau [<a href="https://www.census.gov/data/developers/data-sets/acs-5year.html" target="_blank">2</a>]</p>
        </div>
      </div>
    </div>
    <div class="cartodb-popup-tip-container">
    </div>
</div>



##-----------------------------LEGEND-----------------------------##
<div class='cartodb-legend choropleth'>	
<div class="legend-title" style="text-align: center; font-size:14px; margin-bottom:-16px; text-transform:capitalize;">Fully Vaccinated</div>
<ul>
	<li class="min" style="font-size:14px;">
		0%
	</li>
	<li class="max"style="font-size:14px;">
		25%
	</li>
	<li class="graph count_441">
	<div class="colors">
	<div class="quartile" style="background-color:#FFFFCC"></div>
	<div class="quartile" style="background-color:#C7E9B4"></div>
	<div class="quartile" style="background-color:#7FCDBB"></div>
	<div class="quartile" style="background-color:#41B6C4"></div>
	<div class="quartile" style="background-color:#1D91C0"></div>
	<div class="quartile" style="background-color:#225EA8"></div>
	<div class="quartile" style="background-color:#0C2C84"></div>
	</div>
	</li>
</ul>
</div>