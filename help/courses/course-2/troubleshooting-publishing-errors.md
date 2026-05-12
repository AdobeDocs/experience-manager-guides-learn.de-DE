---
title: Fehlerbehebung bei Veröffentlichungsfehlern
description: Fehlerbehebung bei Veröffentlichungsfehlern in [!DNL Adobe Experience Manager Guides]
exl-id: b37ea3e7-59cf-4fc5-8fae-e1fadd26f8d8
TQID: https://experienceleague.adobe.com/xUPH5-Fh7uZDO6jaITHCsZfUmVuNtNrxoiAxSRkHvBo
product_v2: id: fae5e35a-80c9-4b94-9352-1a060a6aab1did: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a3bd6397-2eb2-4908-a61c-226e26855dca
subfeature_v2: id: fd6cc9e1-e5e5-494e-b7b1-a32f2d6cd7c9
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: c1579802-ddd4-4214-8a91-97b2066abe11
source-git-commit: 27ffc636d63300fb2e99903d92cab12f0cfcbb25
workflow-type: tm+mt
source-wordcount: 436
ht-degree: 0%

---

# Fehlerbehebung bei Veröffentlichungsfehlern

Das Veröffentlichen einer Karte ist in der Regel einfach. Öffnen Sie die Zuordnung, wählen Sie eine Ausgabevorgabe aus und generieren Sie eine Ausgabe! Wenn eine Zuordnung oder ihre Themen jedoch Fehler enthalten, kann die Ausgabegenerierung fehlschlagen. In diesem Fall ist es wichtig zu wissen, wie Fehler behoben werden können.

>[!VIDEO](https://video.tv.adobe.com/v/338990?quality=12&learn=on)

## Vorbereitung für die Übung

Beispieldateien für die Übung können hier heruntergeladen werden.

[Übung-Download](assets/exercises/publishing-basic-to-advanced.zip)

## Häufige Ursachen für Veröffentlichungsfehler

Es können Fehler in den Quellinhalt eingeführt werden. Beispiel:

* Falsch benannte Dateipfadreferenz

* Falsch benannter Ordner

* Fehlende Grafik oder Datei

* Falsch konfigurierte Inhaltsreferenz

* Fehlerhafter Querverweis

* Fehler in den Werten für ein Attribut (z. B. eine Zeichenfolge statt einer Zahl)

* Falsche Einrichtung der von [!DNL AEM Guides] verwendeten Komponenten

## Auswirkungen von Fehlern

Ein Fehler kann geringfügig sein und zu einem einfachen Hinweis führen, der Sie darüber informiert, dass eine Datei nicht erfolgreich gepackt wurde, oder so schwerwiegend sein kann, dass es zu einem vollständigen Fehler bei der Generierung der Ausgabe kommt. Auf der Registerkarte „Ausgaben“ werden farbcodierte Symbole angezeigt, um Erfolg, Fehler oder Fehler im Zusammenhang mit der Ausgabegenerierung anzuzeigen.

![error-impact](images/error-impact.png)

## Öffnen und Überprüfen von Fehlerprotokollen

Die generierte Protokolldatei kann zur Überprüfung geöffnet werden.

1. Klicken Sie auf **Registerkarte** Ausgaben“ unter „Erzeugte **&quot; auf Datum/Uhrzeit**

   ![error-log](images/error-log.png)

1. Scrollen Sie durch das Fehlerprotokoll.

## Ein- und Ausblenden von Fehlertypen

Das Fehlerprotokoll zeigt jeden Fehlertyp in einer eindeutigen Farbe an.

![navigate-errors](images/navigate-errors.png)

1. **Auswählen** oder **deselektieren** alle Fehlertypen, um die Hervorhebung ein- oder auszublenden.

1. Navigieren Sie in Fehlern mithilfe der **Weiter** oder **Zurück**-Schaltflächen (Pfeile).

## Fehler beheben

Je nach Fehlertyp kann die Auflösung einfach oder komplex sein. Sie kann von einem Autor oder einer Autorin im XML-Editor abgeschlossen werden oder erfordert, dass ein Administrator oder eine Administratorin mit [!DNL AEM Guides] arbeitet. Spezifische Korrekturen hängen von dem Fehler, der Auswirkung und Ihren Organisations-Workflows ab.

* Falsch benannte Dateipfadreferenz

  Autoren können den Pfadverweis im Quelldokument aktualisieren.

* Falsch benannter Ordner

  Autoren können den Ordnernamen aktualisieren oder Dateien nach Bedarf verschieben.

* Fehlende Grafik oder Datei

  Autoren können fehlende Grafiken/Dateien hochladen, eine Grafik/Datei umbenennen oder eine Grafik/Datei verschieben

* Falsch konfigurierte Inhaltsreferenz

  Autoren können die Position des referenzierten Inhalts korrigieren oder den Pfad zur Inhaltsreferenz ändern.

* Fehlerhafter Querverweis

  Autoren können die Position der Querverweise korrigieren oder den Namen oder die Eigenschaften der Zieldatei ändern

* Fehler in den Werten für ein Attribut (z. B. eine Zeichenfolge statt einer Zahl)

  Autoren können das Attribut auf einen korrekten Wert aktualisieren, oder Admins können das System aktualisieren, um neue Werte zu unterstützen.

* Falsche Einrichtung der von [!DNL AEM Guides] verwendeten Komponenten

  Admins können die Installation des Systems, seine Komponenten oder Berechtigungen aktualisieren.
