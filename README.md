AngularJS country/state select
======================

Country/state selects are AngularJS directives for picking countries/states from a list.

Based on this work: https://github.com/banafederico/angularjs-country-select, but:

1. Updated for Angular 1.3.x
2. States directive added.
3. Structure changed to code:name, so in select you will get states by name and in model code in 2 digit format : ```US```.

How to
----------------------

1. Add the markup ```<country-select ng-model="anyModelNameForCountry"></country-select>```
or ```<state-select ng-model="anyModelNameForState"></state-select>```
2. Add the dependency to your app's module ```angular.module('myApp', ['countrySelect','stateSelect']);```