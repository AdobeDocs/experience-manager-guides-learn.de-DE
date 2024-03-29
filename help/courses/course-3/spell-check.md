---
title: Rechtschreibprüfung und Suchen/Ersetzen
description: Rechtschreibprüfung und Suchen/Ersetzen in AEM Handbüchern verwenden
exl-id: 5f39618d-a919-4d3c-a4de-2896f2d1bf20
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '442'
ht-degree: 2%

---

# Rechtschreibprüfung und Suchen/Ersetzen

Der AEM Guides-Editor verfügt über leistungsstarke Funktionen zum Überprüfen und Ersetzen von Rechtschreibfehlern.

>[!VIDEO](https://video.tv.adobe.com/v/342768?quality=12&learn=on)

Rechtschreibfehler korrigieren

1. Suchen Sie einen Fehler in einem offenen Thema, der mit einer roten Unterstreichung angezeigt wird.

1. Halten Sie die Strg-Taste gedrückt und klicken Sie auf die sekundäre Maustaste innerhalb des Wortes.

1. Wählen Sie die richtige Schreibweise aus den Vorschlägen aus.

Wenn die richtige Schreibweise nicht vorgeschlagen wird, können Sie das Wort immer manuell bearbeiten.

## Zur Rechtschreibprüfung AEM

Möglicherweise möchten Sie ein anderes Rechtschreibprüfungs-Tool als das Standardwörterbuch des Browsers verwenden.

1. Navigieren Sie zu **Editor-Einstellungen**.

1. Wählen Sie die **Allgemein** Registerkarte &quot;Einstellungen&quot;.

   ![Konfiguration der Rechtschreibprüfung](images/lesson-11/configure-dictionary.png)

1. Es gibt zwei Optionen:

   - **BrowserRechtschreibprüfung** - die Standardeinstellung, bei der die Rechtschreibprüfung das integrierte Wörterbuch des Browsers verwendet.

   - **Rechtschreibprüfung AEM** - Verwenden Sie dies, um eine benutzerdefinierte Wortliste mithilfe AEM benutzerdefinierten Wörterbuchs zu erstellen.

1. Auswählen **Rechtschreibprüfung AEM**.

1. Klicken Sie auf [!UICONTROL **Speichern**].

Benutzerdefiniertes Wörterbuch konfigurieren

Der Administrator kann die Einstellungen ändern, sodass das AEM Wörterbuch benutzerdefinierte Wörter wie Firmennamen erkennt.

1. Navigieren Sie zum **Instrumente** -Bereich.

1. Anmelden bei **CRXDE Lite**.

   ![Symbol für die CRXDE Lite der AEM](images/lesson-11/crxde-lite.png)

1. Navigieren Sie zum **_/apps/fmdita/config-Knoten_**.

   ![Konfigurationsknoten der CRXDE Lite](images/lesson-11/config-node.png)

1. Erstellen Sie eine neue Datei.

   a. Klicken Sie mit der rechten Maustaste auf den Ordner config .

   b. Auswählen **Erstellen > Datei erstellen**.

   ![Erstellung neuer Wörterbuchdateien](images/lesson-11/new-dictionary-file.png)

   c. Benennen Sie die Datei. _**user_dictionary.txt**_.

   ![Wörterbuchtext eines Benutzers](images/lesson-11/user-dictionary.png)

   d. Klicken [!UICONTROL **OK**].

1. Öffnen Sie die Datei.

1. Fügen Sie eine Liste der Wörter hinzu, die Sie in Ihr benutzerdefiniertes Wörterbuch aufnehmen möchten.

1. Klicken Sie auf [!UICONTROL **Alle speichern**].

1. Schließen Sie die Datei.

Autoren müssen möglicherweise ihre Web-Editor-Sitzung neu starten, um die aktualisierte benutzerdefinierte Wortliste im AEM Wörterbuch zu erhalten.

## Suchen und Ersetzen in einer einzelnen Datei

1. Klicken Sie in der oberen Symbolleiste auf das Symbol Suchen und Ersetzen .

   ![Symbol &quot;Ersetzen&quot;suchen](images/lesson-11/find-replace-icon.png)

1. Geben Sie in der unteren Symbolleiste ein Wort oder eine Wortgruppe ein.

1. Klicken Sie auf [!UICONTROL **Suchen**].

1. Geben Sie bei Bedarf ein Wort ein, um das gefundene Wort zu ersetzen.

1. Klicken [!UICONTROL **Ersetzen**].

## Suchen und Ersetzen im gesamten Repository

1. Navigieren Sie zum **Repository**.

1. Klicken Sie auf [!UICONTROL **Suchen und Ersetzen**] unten links im Bildschirm.

1. Klicken Sie auf [!UICONTROL **Einstellungen anzeigen**] Symbol.

1. Wählen Sie entweder

   - **Checkout-Datei vor Ersetzen** — Wenn dies von einem Administrator aktiviert wird, wird die Datei automatisch ausgecheckt, bevor die Suchbegriffe ersetzt werden.

   - **Nur ganzes Wort** — beschränkt die Suche so, dass nur das genaue eingegebene Wort oder die eingegebene Wortgruppe zurückgegeben wird.

   ![Ersetzen in Repository suchen](images/lesson-11/repository-find-replace.png)

1. Klicken Sie auf [!UICONTROL **Filter anwenden**] -Symbol, um den Pfad im Repository auszuwählen, in dem Sie die Suche durchführen möchten.

1. Geben Sie die Begriffe zu Suchen und Ersetzen ein.

1. Wählen Sie bei Bedarf **Neue Version erstellen nach Ersetzen**.

1. Klicken Sie auf [!UICONTROL **Suchen**].

1. Öffnen Sie die gewünschte Datei und navigieren Sie mit den Pfeilen von einem gefundenen Ergebnis zum nächsten.

   ![Suchen Sie nach Ersetzen der Navigations-Benutzeroberfläche](images/lesson-11/find-replace-navigation.png)
