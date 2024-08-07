---
title: Fehlerbehebung bei Veröffentlichungsfehlern
description: Fehlerbehebung bei Veröffentlichungsfehlern in [!DNL Adobe Experience Manager Guides]
exl-id: b37ea3e7-59cf-4fc5-8fae-e1fadd26f8d8
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---

# Fehlerbehebung bei Veröffentlichungsfehlern

Das Veröffentlichen einer Karte ist normalerweise einfach. Öffnen Sie die Karte, wählen Sie eine Ausgabevorgabe aus und generieren Sie die Ausgabe! Wenn jedoch eine Zuordnung oder deren Themen Fehler enthalten, kann die Generierung der Ausgabe fehlschlagen. In diesem Fall ist es wichtig zu wissen, wie eine Fehlerbehebung durchgeführt werden kann.

>[!VIDEO](https://video.tv.adobe.com/v/338990?quality=12&learn=on)

## Vorbereitung der Übung

Hier können Sie Beispieldateien für die Übung herunterladen.

[Übung-Download](assets/exercises/publishing-basic-to-advanced.zip)

## Häufige Ursachen für Veröffentlichungsfehler

In den Quellinhalt können Fehler eingefügt werden. Zum Beispiel:

* Falsch benannter Dateipfadverweis

* Falsch benannter Ordner

* Fehlende Grafik oder Datei

* Falsch konfigurierte Inhaltsreferenz

* Beschädigte Querverweise

* Fehler in den Werten für ein Attribut (z. B. eine Zeichenfolge anstelle einer Zahl)

* Falsche Einrichtung der von [!DNL AEM Guides] verwendeten Komponenten

## Auswirkungen von Fehlern

Ein Fehler kann geringfügig sein und dazu führen, dass eine Datei nicht erfolgreich gepackt wurde, oder dass sie so schwerwiegend ist, dass die Ausgabe vollständig fehlschlägt. Auf der Registerkarte &quot;Ausgaben&quot;werden farbcodierte Symbole angezeigt, die Erfolg, Fehler oder Fehler im Zusammenhang mit der Ausgabegenerierung anzeigen.

![error-impact](images/error-impact.png)

## Fehlerprotokolle öffnen und überprüfen

Die generierte Protokolldatei kann zur Überprüfung geöffnet werden.

1. Klicken Sie auf der Registerkarte **Ausgaben** auf das Datum/die Uhrzeit unter &quot;Generiert am&quot;.****

   ![error-log](images/error-log.png)

1. Scrollen Sie durch das Fehlerprotokoll.

## Ein- und Ausblenden von Fehlertypen

Das Fehlerprotokoll zeigt jeden Fehlertyp in einer eindeutigen Farbe an.

![navigate-errors](images/navigate-errors.png)

1. **Wählen Sie** oder **heben Sie die Auswahl** eines beliebigen Fehlertyps auf, um die Hervorhebung ein- oder auszublenden.

1. Navigieren Sie mit den Schaltflächen **Weiter** oder **Zurück** (Pfeile) zu Fehlern.

## Fehlerbehebung

Je nach Fehlertyp kann die Auflösung einfach oder komplex sein. Sie kann von einem Autor im XML-Editor ausgefüllt werden oder erfordern, dass ein Administrator mit [!DNL AEM Guides] arbeitet. Die spezifischen Korrekturen hängen vom Fehler, den Auswirkungen und Ihren Organisations-Workflows ab.

* Falsch benannter Dateipfadverweis

      Autoren können den Pfadverweis im Quelldokument aktualisieren.
     
  
* Falsch benannter Ordner

      Autoren können den Ordnernamen aktualisieren oder Dateien nach Bedarf verschieben.
     
  
* Fehlende Grafik oder Datei

      Autoren können eine fehlende Grafik/Datei hochladen, eine Grafik/Datei umbenennen oder eine Grafik/Datei verschieben
     
  
* Falsch konfigurierte Inhaltsreferenz

      Autoren können den Speicherort des referenzierten Inhalts korrigieren oder den Pfad zum Inhaltsverweis ändern.
     
  
* Beschädigte Querverweise

      Autoren können den Speicherort korrigieren, auf den der Querverweis verweist, oder den Namen oder die Eigenschaften der Zieldatei ändern
     
  
* Fehler in den Werten für ein Attribut (z. B. eine Zeichenfolge anstelle einer Zahl)

      Autoren können das Attribut auf einen richtigen Wert aktualisieren oder Administratoren können das System aktualisieren, um neue Werte zu unterstützen.
     
  
* Falsche Einrichtung der von [!DNL AEM Guides] verwendeten Komponenten

      Administratoren können die Installation des Systems, seiner Komponenten oder Berechtigungen aktualisieren.
     
  