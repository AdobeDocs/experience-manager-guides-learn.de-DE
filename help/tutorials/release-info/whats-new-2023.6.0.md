---
title: Versionshinweise | Neue Funktionen in der Adobe Experience Manager-Anleitung, Version Juni 2023
description: Erfahren Sie mehr über die neuen und verbesserten Funktionen in der Version von Adobe Experience Manager Guides as a Cloud Service im Juni 2023.
source-git-commit: 5670b4a8f34916c7ff415680c5ddcfab6e9618e6
workflow-type: tm+mt
source-wordcount: '1129'
ht-degree: 0%

---

# Neue Funktionen in der Version von Adobe Experience Manager Guides as a Cloud Service im Juni 2023

Dieser Artikel behandelt die neuen und verbesserten Funktionen in der Version vom Juni 2023 der Adobe Experience Manager-Handbücher (später als *AEM as a Cloud Service Handbücher*).

Weitere Informationen zu den Upgrade-Anweisungen, der Kompatibilitätsmatrix und den in dieser Version behobenen Problemen finden Sie in der [Versionshinweise](release-notes-2023.6.0.md) Artikel.

## Bericht &quot;Fehlerhafte Links&quot;im Web-Editor

Mit AEM Guides können Sie die Gesamtvollständigkeit Ihrer technischen Dokumente überprüfen und Berichte aus dem Web-Editor erstellen. Ab der Version Juni 2023 bieten Ihnen AEM Handbücher die Möglichkeit, fehlerhafte Links anzuzeigen und zu reparieren. Dies ist ein sehr nützlicher Bericht, der Ihnen bei der Verwaltung Ihrer fehlerhaften Links hilft. Sie können die fehlerhaften Links in Ihrer DITA-Zuordnung einfach anzeigen und sie auch beheben.
![](assets/broken-link-report.png){width="800" align="left"}

Wenn Sie einen Link korrigieren, wird er nicht mehr unter der Liste der fehlerhaften Links angezeigt.

Weitere Informationen finden Sie unter [Fehlerbehebung bei fehlerhaften Links](../user-guide/reports-web-editor.md#report-broken-links).

## Umbenennen und Verschieben von Dateien in der Repository-Ansicht

Jetzt können Sie eine Datei auch umbenennen oder aus dem Repository-Bereich verschieben. Diese Funktion ist sehr praktisch und erleichtert die Verwaltung Ihrer Dateien über das Repository-Bedienfeld. Sie können eine Datei auswählen und sie umbenennen oder verschieben mithilfe der **Optionen** für die ausgewählte Datei. AEM Handbücher zeigt eine Erfolgsmeldung an, wenn Sie eine Datei verschieben oder umbenennen.

![](assets/rename-move-assets.png){width="650" align="left"}

Weitere Informationen zum Menü Optionen einer Datei finden Sie unter **Repository-Ansicht** Funktionsbeschreibung in [Linke Leiste](../user-guide/web-editor-features.md#id2051EA0M0HS) Abschnitt.

## Native PDF-Verbesserungen

### Wasserzeichen zur PDF-Ausgabe für Entwürfe hinzufügen

Jetzt können Sie ein Wasserzeichen zur PDF-Ausgabe des Dokuments hinzufügen, das noch nicht genehmigt wurde. Dieses Wasserzeichen wird nicht angezeigt, wenn Sie die PDF für das Dokument im Dokumentstatus &quot;Genehmigt&quot;generieren. Sie können beispielsweise einen Wasserzeichenentwurf für Ihre PDF-Ausgabe hinzufügen.

Weitere Informationen finden Sie unter [Hinzufügen eines Wasserzeichens zur PDF-Ausgabe für Entwürfe von Dokumenten](../native-pdf/use-javascript-content-style.md#watermark-draft-document).

### Unterstützung für Sprachvariablen in DITA-Elementen

AEM Guides unterstützen die Sprachvariablen. Diese Variablen sind sehr nützlich, um lokalisierte Zeichenfolgen für Elemente wie Hinweis, Tipp, Warnung, Vorsicht zu generieren. Beispielsweise können Sie Ihre NOTE auf folgende Weise in der PDF-Ausgabe präsentieren: Deutsch: Notiz Spanisch: Hinweis

### Unterstützung für Sprachvariablen in der Fußzeile der Seite

Sie können einer laufenden Kopf- oder Fußzeile auf der Übergeordneten Seite eines Dokuments eine Sprachvariable hinzufügen. Die -Variable wird auf allen Textseiten des Dokuments angezeigt, auf die diese Übergeordnete Seite angewendet wird. Beispiel: 1 von 1 Seite.
Sie können sie auch verwenden, um die Zahlen in verschiedenen Sprachen anzuzeigen.

### Lokalisierte Präfixe für Ihr Inhaltsverzeichnis

Sie haben auch die Funktion, lokalisierte Begriffe anzuzeigen, die zum Präfix in Ihren Überschriften verwendet werden sollen.
Sie können beispielsweise das Präfix &quot;Kapitel&quot;auf folgende Weise in der PDF-Ausgabe präsentieren: Deutsch: Kapitel Spanisch: Capítulo

### Möglichkeit zur Verwendung AEM Metadaten in PDF-Layouts


Metadaten sind die Beschreibung oder Definition Ihres Inhalts. Diese Metadaten werden in Ihrem Quell-DITA-Map-Inhalt gespeichert.

Jetzt können Sie in AEM Handbüchern auch die Metadateneigenschaften Ihrer Assets auswählen und sie zum Seitenlayout hinzufügen. Anschließend wählt AEM Guides diese Metadateneigenschaften Ihrer Assets aus und veröffentlicht sie in Ihrer PDF-Ausgabe.


![](assets/native-pdf-metadata-asset.png){width="550" align="left"}

>[!NOTE]
>
> AEM Guides unterstützen auch die Metadateneigenschaften für Ihre DITA-Maps.

Weitere Informationen finden Sie unter [Felder und Metadaten hinzufügen](../native-pdf/design-page-layout.md#add-fields-metadata).


## Verbesserungen bei Schemata

### Verwenden Sie Berichtanweisungen, um in Schemata nach Regeln zu suchen

AEM Guides unterstützen jetzt auch die Berichtanweisungen mit dem Schema. Eine Berichtanweisung generiert eine Meldung, wenn eine Testanweisung als &quot;true&quot;ausgewertet wird. Wenn Sie beispielsweise eine Kurzbeschreibung von 150 Zeichen oder weniger wünschen, können Sie eine Berichtanweisung definieren, um die Themen zu überprüfen, bei denen die Kurzbeschreibung mehr als 150 Zeichen umfasst.

Weitere Informationen finden Sie unter [Verwenden Sie Asset- und Berichtanweisungen, um nach Regeln zu suchen.](../user-guide/support-schematron-file.md#schematron-assert-report).

### Verwenden von Regex-Ausdrücken

Sie können auch Regex-Ausdrücke verwenden, um eine Regel mit der Funktion matches() zu definieren und dann mithilfe der Schematron-Datei eine Validierung durchzuführen.

Weitere Informationen finden Sie unter [Verwenden von Regex-Ausdrücken](../user-guide/support-schematron-file.md#schematron-assert-report).


### Abstrakte Muster definieren

AEM Guides unterstützen auch abstrakte Muster in Schematron. Sie können allgemeine abstrakte Muster definieren und diese abstrakten Muster wiederverwenden. Abstrakte Muster können Ihr Schema vereinfachen und Ihnen auch bei der Verwaltung und Aktualisierung Ihrer Validierungslogik helfen.


Weitere Informationen finden Sie unter [Abstrakte Muster definieren](../user-guide/support-schematron-file.md#schematron-abstract-patterns).

## Navigieren Sie vom Web Editor zur AEM Startseite .

Jetzt können Sie einfach vom Web-Editor zur AEM-Startseite navigieren.

![](assets/web-editor-launch-page.png){width="800" align="left"}

* Klicken Sie auf **Handbücher** Symbol (![](assets/aem-guides-icon.png) ), um zur AEM Navigationsseite zurückzukehren.


Weitere Informationen finden Sie unter [AEM](../user-guide/web-editor-launch-editor.md#id2056BG00RZJ).

## Umgang mit hierarchischen Definitionen von Betreffdefinitionen und Auflistungen

AEM Guides verfügen über die leistungsstarke Funktion zum Erstellen von Themenschemas, die eine spezielle Form von DITA-Maps darstellen, die zur Definition von taxonomischen Objekten und kontrollierten Werten verwendet werden. Jetzt können AEM Guides auch die Definition des Betreffs in einer Zuordnung und die Auflistungsdefinitionen in einer anderen Zuordnung definieren. Anschließend können Sie die Zuordnungsreferenz hinzufügen und das Betreffschema verwenden.
Die Verweise auf die Betreffauflistung werden in derselben Zuordnung oder der referenzierten Zuordnung aufgelöst.

Weitere Informationen zum Umgang mit hierarchischen Definitionen von Betreffdefinitionen und Auflistungen finden Sie in der **Betrifft** Funktionsbeschreibung in [Linke Leiste](../user-guide/web-editor-features.md#id2051EA0M0HS) Abschnitt.

## Unterstützung des XLIFF-Formats bei der Übersetzung

AEM Guides unterstützen auch das XLIFF-Format (XML Localization Interchange File Format) bei der Übersetzung. Jetzt können Sie auch **Erstellen eines neuen XLIFF-Übersetzungsprojekts** , um den XML-Inhalt in das XLIFF-Format zu konvertieren.
Mithilfe dieses Formats können Sie den Inhalt in das XLIFF-Format des Branchenstandards exportieren und dann den Übersetzungsanbietern dasselbe bereitstellen. Weitere Informationen finden Sie unter [Erstellen eines Übersetzungsprojekts](../user-guide/translate-documents-web-editor.md#create-translation-project).

![](assets/translation-project-types.png){width="350" align="left"}



## Verbessertes Bedienfeld &quot;Favoriten&quot;

Mithilfe AEM Handbücher können Sie eine Sammlung oder Favoritenliste Ihrer Dateien und Ordner erstellen und diese einfach verwenden. Jetzt **Optionen** ist auch im Menü **Favoriten** Bereich. Sie können die ausgewählte Sammlung umbenennen oder aus der **Optionen** Menü. Sie können die **Aktualisieren** , um eine neue Liste von Dateien oder Ordnern aus dem Repository zu erhalten. Sie können den Ordnerinhalt auch in der Assets-Benutzeroberfläche anzeigen.

![](assets/favorites-options.png){width="650" align="left"}

>[!NOTE]
>
> Sie können die Liste auch mit dem **Aktualisieren** Symbol oben.

Weitere Informationen finden Sie unter **Optionen** Menü einer Favoriten-Sammlung, siehe **Favoriten** Funktionsbeschreibung in [Linke Leiste](../user-guide/web-editor-features.md#id2051EA0M0HS) Abschnitt.

## Wechseln zum Systemdesign

Sie können jetzt auch das Gerätedesign verwenden. Verwenden der **Benutzereinstellungen** können Sie AEM Guides so konfigurieren, dass je nach Thema Ihres Geräts automatisch zwischen hellen und dunklen Themen umgeschaltet wird.

![](assets/device-theme-user-preferences.png){width="550" align="left"}

Weitere Informationen finden Sie unter **Benutzereinstellungen** Funktionsbeschreibung in [Hauptsymbolleiste](../user-guide/web-editor-features.md#id2051EA0G05Z) Abschnitt.