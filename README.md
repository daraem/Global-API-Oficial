# Global-API-Oficial
These endpoints have been extracted from Global android app.

# Endpoints

-- Base --

BASE_URL: "https://app.guaguasglobal.com:44043/App_MiLineaGlobal-Project-context-root/jersey/"
ALTERNATIVE_BASE_URL: "http://80.28.248.205:8086/App_MiLineaGlobal-Project-context-root/jersey/"

BASE_2_URL: http://sat2globalapp.com:44040/App_GlobalSW-Project-context-root/jersey/
ALTERNATIVE_BASE_2_URL: http://80.28.248.205:8086/App_GlobalSW-Project-context-root/jersey/

-- Endpoints --

-- BASE_URL --
/paradas/{id}
/paradas/{id}/vehiculoscercanos
/paradas/{id}/variantes
/paradasjson?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --
/tarifas?lang={lang_code} # tarifas?lang=es
/puntosventa?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --
/lineas
/lineas/{linea}/horarios?lang={lang_code}&sentido={0/1}
/lineas/{linea}/horarios?lang={lang_code}&sentido={0/1}&fecha={?} -- Not tested --
/lineas/{linea}?opcion=solovariantes
/lineas?lat={latitude}&lon={longitude}&dist={distance} -- Not tested --
/lineas/detalleposicion/{linea}?lat={latitude}&lon={longitude} -- Not tested --
/lineas/detalleposicion/{linea}
/posicionvehiculos
/lineas/{linea}?opcion=paradas
/lineas/{linea}?opcion=trazados
/version?id={?}
/notificacionesapp?lang={lang_code}
/configuracion?lang={lang_code}

-- BASE_2_URL --
/obtenersaldotm?tarjeta={tarjeta_id}&titulo={nombre?}&nif={nif} -- Not tested --
/titulos?lang={lang_code}
