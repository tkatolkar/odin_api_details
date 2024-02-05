* __API :__ * calc/<*slug:slug*>/nodescenarios/<*slug:nodescenario_slug*>/params/"
  
* __View :__ OdinCalcNodeScenariosParamsView

* __API Name :__ calc_nodescenarios_params


#### Method: GET

* __Response format:__ Dictionary of dictionary
* __Keys in Dictionary:__
   * node_scenario_slug : *str*
   * params : *dict*
     * __Keys in 'params' Dictionary:__
        * capacity : *str*
        * duration : *str*  
        * min_cycles : *str*
        * max_cycles : *str*
        * rt_mode : *str*
        * decay : *str*
        * chg_eff : *str*
        * dischg_eff : *str*
        * regup_eff : *str*
        * regdn_eff : *str*
        * spin_eff : *str*
        * nspin_eff : *str*
        * annual_degradation_rate : *str*
        * battery_life : *str*
        * cycle_life : *str*
        * augmentation_cost : *str*
        * capital_cost : *str*
        * soc_start : *str*
        * soc_end : *str*
        * soc_max : *str*
        * soc_min : *str*
        * poi_limit : *str*
        * grid_charge : *str*
        * ptc_min : *str*
        * cross_zero : *str*
        * energy_switch : *str*
        * regup : *str*
        * regdn : *str*
        * spin : *str*
        * nonspin_switch : *str*
        * cycle_cost_switch : *str*
        * degradation_switch : *str*
        * da_prices_only : *str*
        * operational_months : *str*
        * model : *str* 
