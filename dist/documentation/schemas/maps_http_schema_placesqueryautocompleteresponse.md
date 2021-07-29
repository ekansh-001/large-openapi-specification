<!--- This is a generated file, do not edit! -->
<!--- [START maps_http_schema_placesqueryautocompleteresponse] -->
<h3 class="schema-object" id="PlacesQueryAutocompleteResponse">Places Autocomplete Response Body</h3>

type: `object`

| Field           | Required     | Type                                                                                                   | Description                                                                                                                                                                                                                        |
| :-------------- | ------------ | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `predictions`   | **required** | Array&lt;[PlaceAutocompletePrediction](#PlaceAutocompletePrediction "PlaceAutocompletePrediction")&gt; | <div class="ref-property-description"><p>Contains an array of predictions.</p><p>See <a href="#PlaceAutocompletePrediction">PlaceAutocompletePrediction</a> for more information.</div>                                            |
| `status`        | **required** | [PlacesStatus](#PlacesStatus "PlacesStatus")                                                           | <div class="ref-property-description"><p>Contains metadata on the request.</p><p>See <a href="#PlacesStatus">PlacesStatus</a> for more information.</div>                                                                          |
| `error_message` | optional     | string                                                                                                 | <div class="nonref-property-description"><p>Contains additional information about the request.</p></div>                                                                                                                           |
| `info_messages` | optional     | Array&lt;string&gt;                                                                                    | <div class="nonref-property-description"><p>Contains additional information about the request. This field is only returned for successful requests. It may not always be returned, and its content is subject to change.</p></div> |

<!--- [END maps_http_schema_placesqueryautocompleteresponse] -->