# Global-API-Oficial
These endpoints have been extracted from Global android app.

# Endpoints

## Base
BASE_URL: "https://app.guaguasglobal.com:44043/App_MiLineaGlobal-Project-context-root/jersey/"<br>
ALTERNATIVE_BASE_URL: "http://80.28.248.205:8086/App_MiLineaGlobal-Project-context-root/jersey/"<br>
<br>
BASE_2_URL: http://sat2globalapp.com:44040/App_GlobalSW-Project-context-root/jersey/<br>
ALTERNATIVE_BASE_2_URL: http://80.28.248.205:8086/App_GlobalSW-Project-context-root/jersey/<br>

## Endpoints

### BASE_URL
/paradas/{id}<br>
/paradas/{id}/vehiculoscercanos<br>
/paradas/{id}/variantes<br>
/paradasjson?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --<br>
/tarifas?lang={lang_code} # tarifas?lang=es<br>
/puntosventa?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --<br>
/lineas<br>
/lineas/{linea}/horarios?lang={lang_code}&sentido={0/1}<br>
/lineas/{linea}/horarios?lang={lang_code}&sentido={0/1}&fecha={?} -- Not tested --<br>
/lineas/{linea}?opcion=solovariantes<br>
/lineas?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --<br>
/lineas/detalleposicion/{linea}?lat={latitude}&lon={longitude} -- Not tested --<br>
/lineas/detalleposicion/{linea}<br>
/posicionvehiculos<br>
/lineas/{linea}?opcion=paradas<br>
/lineas/{linea}?opcion=trazados<br>
/version?id={?}<br>
/notificacionesapp?lang={lang_code}<br>
/configuracion?lang={lang_code}<br>

### BASE_2_URL
/obtenersaldotm?tarjeta={tarjeta_id}&titulo={nombre?}&nif={nif} -- Not tested --<br>
/titulos?lang={lang_code}<br>
