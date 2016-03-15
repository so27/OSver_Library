# OSver_Library
Library für Basic 4 Android zur Klartextdarstellung des verwendeten Betriebssystems.

Hierbei handelt es sich um eine kleine Bibliothek aller bisherigen Android™ Versionen. Über die entsprechende SDK-Nr. wird hiermit das dazugehörende Betriebssystem in Klartext angezeigt.

Die Verwendung ist dabei ganz simpel.

  Dim OS as OSver (in die Globals)
  OS.Initialize
  Log(OS.SDKname)
	Log(OS.WhatSDKnr)
	
	SDKname wird als String und WhatSDKnr wird als Integer ausgegeben.
