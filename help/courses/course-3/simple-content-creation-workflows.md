---
title: Einfache Workflows zur Inhaltserstellung
description: Erstellen von Inhalten in AEM Guides
exl-id: e4b8e512-0688-44f7-b981-78af33b57b08
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '719'
ht-degree: 2%

---

# Workflows zur einfachen Inhaltserstellung

Der AEM Guides-Editor verfügt über mehrere Tastaturbefehle, die den Arbeitsablauf für die Inhaltserstellung vereinfachen. Mit diesen Tastaturbefehlen können Benutzer schnell Bilder hinzufügen und ändern, mit mehreren Themen gleichzeitig arbeiten, Fehler korrigieren, Themenversionen herunterladen und mit PDF und Beschriftungen arbeiten.

>[!VIDEO](https://video.tv.adobe.com/v/342770?quality=12&learn=on)

## Bild hinzufügen

Bilder können direkt von einem lokalen Laufwerk aus hinzugefügt werden.

1. Ziehen Sie das Bild direkt in das Thema. Das Dialogfeld **Assets hochladen** wird angezeigt.

   ![Assets-Dialogfeld hochladen](images/lesson-15/upload-assets-dialog.png)

1. Ändern Sie den Ordnerpfad zum gewünschten Bildspeicherort.

1. Ändern Sie den Namen des Bildes in einen für seinen Zweck repräsentativen Namen.

1. Klicken Sie auf [!UICONTROL **Hochladen**].

## Bild ändern

1. Ändern Sie die Größe eines Bildes durch Ziehen und Ablegen einer Ecke.

1. Verschieben Sie ein Bild durch Ziehen und Ablegen an eine andere Position innerhalb des Themas.

1. Verwenden Sie **Inhaltseigenschaften** auf der rechten Seite, um die

   - scale

   - position

   - Ausrichtung oder

   - andere Attribute.

   ![Inhaltseigenschaften](images/lesson-15/content-properties.png)

## Arbeiten mit mehreren Themen

Die Aufspaltung ist beim Vergleichen von Themen, beim Kopieren und Einfügen zwischen Themen oder beim Ziehen und Ablegen von Inhalten von einem Thema zum anderen hilfreich.

1. Öffnen Sie zwei oder mehr verwandte Themen.

1. Klicken Sie auf die Registerkarte Titel einer Datei, um das Kontextmenü zu öffnen.

1. Wählen Sie [!UICONTROL **Aufspaltung**] aus.

1. Wählen Sie **Right** aus.

   ![Aufspaltungsansicht](images/lesson-15/split-view.png)

## Korrigieren typografischer Fehler

1. Suchen Sie das Wort oder die Wortgruppe, das/die den Fehler enthält.

1. Halten Sie [!UICONTROL **Strg**] gedrückt.

1. Klicken Sie auf die sekundäre Maustaste auf den Fehler.

1. Wählen Sie die richtige Schreibweise aus.

Der Fehler wurde im Thementext korrigiert.

## Thema-PDF herunterladen

Benutzer können eine PDF des aktuellen Themas herunterladen, um sie zu markieren oder für andere freizugeben.

1. Klicken Sie oben rechts im Bildschirm auf [!UICONTROL **Vorschau**] .

1. Klicken Sie auf das [!UICONTROL **PDF-Symbol**] über dem Thema. Ein Dialogfeld wird angezeigt.

   ![PDF-Export](images/lesson-15/pdf-export.png)

1. Füllen Sie bei Bedarf die Informationen für **Transformationsname** oder **DITA-OT Befehlszeilenargumente** aus. Beachten Sie, dass eine PDF immer noch generiert wird, wenn alle Felder leer gelassen werden.

1. Klicken Sie auf [!UICONTROL **Herunterladen**]. Die PDF generiert.

1. Verwenden Sie verfügbare Symbole, um das PDF-Thema zu konfigurieren, herunterzuladen oder freizugeben.

## Suchen Sie ein Thema im Repository oder in der Zuordnung

1. Öffnen Sie das Thema.

1. Klicken Sie auf die sekundäre Maustaste auf der Registerkarte Titel .

1. Wählen Sie &quot;**Suchen in**&quot;.

1. Wählen Sie entweder **Repository** oder **Map** aus, um zum gewünschten Themenspeicherort zu springen.

## Thema verändern

1. Nehmen Sie eine Änderung an einem Thema vor.

1. Speichern Sie das Thema.

1. Klicken Sie im Menü oben links auf das Symbol **Repository** .

   ![Repository-Symbol](images/lesson-15/repository-icon.png)

1. Fügen Sie im Dialogfeld **Kommentare für neue Version** hinzu.

   ![Dialogfeld &quot;Neue Version&quot;](images/lesson-15/version-dialog.png)

1. Klicken Sie auf [!UICONTROL **Speichern**].

Die Versionsnummer wird aktualisiert.

## Versionshinweise laden

Es kann schwierig sein, den Status eines Themas nur anhand der Versionsnummer zu verfolgen. Beschriftungen erleichtern die Identifizierung des genauen Zustands eines Themas, das mehrfach überarbeitet wurde.

1. Wählen Sie ein **Ordnerprofil** aus.

1. Konfigurieren Sie im Ordnerprofil den XML-Editor.

   a. Wählen Sie oben links im Bildschirm die Option Bearbeiten .

   b. Fügen Sie unter &quot;Beschriftungen der XML-Inhaltsversion&quot;entweder ein neues Thema hinzu oder verwenden Sie ein vorhandenes.

   ![Beschriftungen der Inhaltsversion](images/lesson-15/version-labels.png)

1. Wählen Sie [!UICONTROL **Upload**] aus.

1. Wählen Sie eine Datei wie ReviewLabels.json oder eine ähnliche. Weitere Informationen zum Erstellen einer solchen Datei finden Sie in einem anderen Video.

1. Klicken Sie auf [!UICONTROL **Öffnen**].

1. Klicken Sie oben links im Bildschirm &quot;Ordnerprofil&quot;auf [!UICONTROL **Speichern**] .

1. Klicken Sie oben rechts auf [!UICONTROL **Schließen**] .

Versionsbeschriftungen werden jetzt geladen.

## Zuweisen von Versionsbeschriftungen

1. Versionsbeschriftungen laden.

1. Klicken Sie oben links im aktuellen Thema auf das Symbol [!UICONTROL **Benutzereinstellungen**] .

   ![Ordnerprofil](images/lesson-15/folder-profile-icon.png)

1. Wählen Sie dasselbe Ordnerprofil aus, in das bereits Versionsbezeichnungen geladen wurden.

1. Stellen Sie im Dialogfeld Benutzereinstellungen sicher, dass der Basispfad auf dieselben Informationen verweist, auf die das Ordnerprofil angewendet wurde.

   ![Benutzereinstellungen](images/lesson-15/user-preferences.png)

1. Klicken Sie auf [!UICONTROL **Speichern**].

1. Veröffentlichen Sie das Thema.

1. Fügen Sie einen Kommentar hinzu und wählen Sie eine Versionsbezeichnung aus der Dropdown-Liste aus.

   ![Dialogfeld &quot;Neue Versionsbezeichnung&quot;](images/lesson-15/labels-dialog.png)

1. Klicken Sie auf [!UICONTROL **Speichern**].

Die Versionsnummer wird aktualisiert.

## Versionsverlauf und Titel anzeigen

1. Suchen Sie im linken Bereich den aktuellen Thementitel.

1. Klicken Sie auf den Titel, um das Kontextmenü zu öffnen.

1. Wählen Sie [!UICONTROL **In Assets UI anzeigen**] aus.

   ![Assets UI](images/lesson-15/view-assets-ui.png)

   - Der Versionsverlauf mit Bezeichnungen wird auf der linken Seite angezeigt.

   ![Versionsverlauf](images/lesson-15/version-history.png)

1. Klicken Sie auf eine Version, um auf Optionen wie **Auf diese Version zurücksetzen** und **Vorschau der Version** zuzugreifen.

## Neue Vorlage erstellen

Es gibt Vorlagen für Themen und Maps. Administratoren können auf Vorlagen im linken Bereich zugreifen.

1. Klicken Sie im linken Bereich auf [!UICONTROL **Vorlagen**] .

1. Wählen Sie entweder Karte oder Thema aus, um das zugehörige Kontextmenü zu öffnen.

1. Klicken Sie auf , um die neue Vorlage hinzuzufügen.

   ![Neue Themenvorlage](images/lesson-15/version-history.png)

1. Füllen Sie die Felder im daraufhin angezeigten Dialogfeld aus.

Die Shell-Vorlage wird angezeigt, die Beispielinhalt und eine Beispielstruktur enthält.
