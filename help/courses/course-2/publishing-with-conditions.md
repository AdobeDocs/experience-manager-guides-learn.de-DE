---
title: Veröffentlichung mit Bedingungen
description: Veröffentlichung mit Bedingungen mit Adobe Experience Manager Guides
exl-id: ea94824a-884b-447f-9562-e6c629b8133b
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '359'
ht-degree: 4%

---

# Veröffentlichung mit Bedingungen

Durch die bedingte Veröffentlichung kann eine Inhaltsquelle für eine oder mehrere Zielgruppen, Produkte oder Plattformen geschrieben werden. Diese Informationen können dann dynamisch veröffentlicht werden und nur speziell erforderliche Inhalte, die in der Ausgabe enthalten sind.

>[!VIDEO](https://video.tv.adobe.com/v/339041?quality=12&learn=on)

## Vorbereitung der Übung

Hier können Sie Beispieldateien für die Übung herunterladen.

[Übung-Download](assets/exercises/publishing-with-conditions.zip)

## Markieren von Inhalten mit bedingten Attributen

1. Öffnen Sie das zu ändernde Thema.

1. Geben Sie den Text ein, der an Bedingungen geknüpft werden soll. Beispielsweise einen oder mehrere Absätze, eine gesamte Tabelle, eine Abbildung oder andere Inhalte.

   ![Presenting-information](images/presenting-info.png)

1. Wählen Sie den spezifischen Inhalt aus, dem ein bedingtes Attribut zugewiesen werden soll. Beispielsweise einen einzelnen Absatz innerhalb der Quelle.

   ![Vorlagenauswahl](images/template-choice.png)

1. Stellen Sie in der rechten Leiste sicher, dass die Eigenschaften angezeigt werden.

1. Fügen Sie ein Attribut für Zielgruppe, Produkt oder Plattform hinzu.

1. Weisen Sie dem Attribut einen Wert zu. Die Inhaltsanzeige wurde aktualisiert, um bedingte Markierungen anzuzeigen.

   ![Angeben-Vorlage](images/specify-template.png)

## Vorschau bedingter Inhalte

1. Klicken Sie auf **Vorschau**. 

1. Wählen Sie unter **Filter** die Bedingungen aus, die ein- oder ausgeblendet werden sollen, oder heben Sie die Auswahl auf.

1. Wählen Sie **Text der Bedingungen markieren** aus oder heben Sie die Auswahl auf.

   ![Vorschau-Bedingter Inhalt](images/preview-conditional-content.png)

## Bedingungsvorgabe erstellen

Eine Bedingungsvorgabe ist eine Sammlung von Eigenschaften, die definieren, was während der Generierung der Ausgabe ein- oder ausgeschlossen bzw. anderweitig markiert werden soll.

1. Wählen Sie im Map Dashboard die Registerkarte **Bedingungsvorgaben** aus.

1. Klicken Sie auf **Erstellen**.

1. Wählen Sie **Hinzufügen** (oder **Alle hinzufügen**).

1. Benennen Sie die Bedingung.

1. Wählen Sie eine Kombination aus Attribut, Titel und Aktion aus.

   ![create-condition-preset](images/create-condition-preset.png)

1. Wiederholen Sie dies nach Bedarf.

1. Klicken Sie auf **Speichern**.

## Bedingte Ausgabe generieren

Sobald Bedingungen auf Inhalte angewendet wurden, können sie als Ausgabe generiert werden. Dies kann entweder eine Bedingungsvorgabe oder eine DITAval-Datei verwenden.

## Bedingte Ausgabe mithilfe einer Bedingungsvoreinstellung erstellen

1. Wählen Sie die Registerkarte **Ausgabevorgaben** aus.

1. Wählen Sie eine Ausgabevorgabe aus.

1. Klicken Sie auf **Bearbeiten**.

1. Wählen Sie unter **Bedingung anwenden mit** eine Bedingungsvorgabe aus.

   ![generate-Conditional-output](images/generate-conditional-output.png)

1. Klicken Sie auf **Fertig**.

1. Generieren Sie die Ausgabevorgabe und überprüfen Sie den Inhalt.

## Generieren einer bedingten Ausgabe mit einer DITAval-Datei

Die DITAval-Datei kann verwendet werden, um bedingte Inhalte zu veröffentlichen. Dazu muss eine Datei erstellt oder hochgeladen und dann bei der Veröffentlichung referenziert werden.

1. Wählen Sie die Registerkarte **Ausgabevorgaben** aus.

1. Wählen Sie eine Ausgabevorgabe aus.

1. Klicken Sie auf **Bearbeiten**.

1. Wählen Sie unter &quot;Bedingungen anwenden mit&quot;eine DITAval-Datei aus.

   ![generate-using-DITAval](images/generate-using-ditaval.png)

1. Klicken Sie auf **Fertig**.

1. Generieren Sie die Ausgabevorgabe und überprüfen Sie den Inhalt.
