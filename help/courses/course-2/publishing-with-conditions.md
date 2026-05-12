---
title: Veröffentlichung mit Bedingungen
description: Veröffentlichung mit Bedingungen in Adobe Experience Manager Guides
exl-id: ea94824a-884b-447f-9562-e6c629b8133b
TQID: https://experienceleague.adobe.com/Ez-rAJNfPH-Dd2lTd65B1bct4lkhoB2Gi6IKc8-A8gI
product_v2: id: fae5e35a-80c9-4b94-9352-1a060a6aab1did: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a3bd6397-2eb2-4908-a61c-226e26855dca
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
source-git-commit: 27ffc636d63300fb2e99903d92cab12f0cfcbb25
workflow-type: tm+mt
source-wordcount: 371
ht-degree: 4%

---

# Veröffentlichung mit Bedingungen

Bedingte Veröffentlichung ermöglicht das Schreiben einer Inhaltsquelle für eine oder mehrere Zielgruppen, Produkte oder Plattformen. Diese Informationen können dann dynamisch veröffentlicht werden und es können nur speziell erforderliche Inhalte in die Ausgabe aufgenommen werden.

>[!VIDEO](https://video.tv.adobe.com/v/339041?quality=12&learn=on)

## Vorbereitung für die Übung

Beispieldateien für die Übung können hier heruntergeladen werden.

[Übung-Download](assets/exercises/publishing-with-conditions.zip)

## Inhalte mit bedingten Attributen markieren

1. Öffnen Sie das zu ändernde Thema.

1. Geben Sie den Text ein, der bedingt werden soll. Beispielsweise einen oder mehrere Absätze, eine gesamte Tabelle, eine Abbildung oder andere Inhalte.

   ![presenting-information](images/presenting-info.png)

1. Wählen Sie den spezifischen Inhalt aus, dem ein bedingtes Attribut zugewiesen werden soll. Beispiel: ein einzelner Absatz innerhalb der Quelle.

   ![template-choice](images/template-choice.png)

1. Stellen Sie sicher, dass in der rechten Leiste die Eigenschaften angezeigt werden.

1. Attribut für Zielgruppe, Produkt oder Plattform hinzufügen.

1. Weisen Sie dem Attribut einen Wert zu. Die Aktualisierungen der Inhaltsanzeige zeigen jetzt bedingtes Markup an.

   ![Vorlage angeben](images/specify-template.png)

## Vorschau von bedingten Inhalten

1. Klicken Sie auf **Vorschau**.

1. Wählen **unter &quot;**&quot; die Bedingungen zum Ein- oder Ausblenden aus bzw. heben Sie die Auswahl auf.

1. Auswählen oder Aufheben der Auswahl **Hervorheben von Bedingungstext**.

   ![preview-conditional-content](images/preview-conditional-content.png)

## Erstellen einer Bedingungsvorgabe

Eine Bedingungsvorgabe ist eine Sammlung von Eigenschaften, die definieren, was während der Generierung der Ausgabe eingeschlossen, ausgeschlossen oder anderweitig gekennzeichnet werden soll.

1. Wählen Sie im Zuordnungs-Dashboard die Registerkarte **Bedingungsvorgaben** aus.

1. Klicken Sie auf **Erstellen**.

1. Wählen Sie **Hinzufügen** (oder **Alle hinzufügen**) aus.

1. Benennen Sie die Bedingung.

1. Wählen Sie eine Kombination aus Attribut, Bezeichnung und Aktion aus.

   ![create-condition-preset](images/create-condition-preset.png)

1. Wiederholen Sie dies nach Bedarf.

1. Klicken Sie auf **Speichern**.

## Bedingte Ausgabe erzeugen

Sobald Bedingungen auf Inhalte angewendet wurden, können sie als Ausgabe generiert werden. Dabei kann entweder eine Bedingungsvorgabe oder eine DITAval-Datei verwendet werden.

## Erstellen einer bedingten Ausgabe mithilfe einer Bedingungsvorgabe

1. Wählen Sie die **Ausgabevorgaben** aus.

1. Wählen Sie eine Ausgabevorgabe aus.

1. Klicken Sie auf **Bearbeiten**.

1. Wählen **unter „Bedingung anwenden mit** eine Bedingungsvorgabe aus.

   ![generate-conditional-output](images/generate-conditional-output.png)

1. Klicken Sie auf **Fertig**.

1. Erzeugen Sie die Ausgabevorgabe und überprüfen Sie den Inhalt.

## Generieren einer bedingten Ausgabe mithilfe einer DITAval-Datei

Die DITAval-Datei kann zum Veröffentlichen bedingter Inhalte verwendet werden. Dazu muss eine Datei erstellt oder hochgeladen und dann bei der Veröffentlichung referenziert werden.

1. Wählen Sie die **Ausgabevorgaben** aus.

1. Wählen Sie eine Ausgabevorgabe aus.

1. Klicken Sie auf **Bearbeiten**.

1. Wählen Sie unter Bedingung anwenden mithilfe einer DITAval-Datei aus.

   ![generate-using-DITAval](images/generate-using-ditaval.png)

1. Klicken Sie auf **Fertig**.

1. Erzeugen Sie die Ausgabevorgabe und überprüfen Sie den Inhalt.
