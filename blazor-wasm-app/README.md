# Blazor WebAssembly App

Dieses Projekt ist eine Blazor WebAssembly-Anwendung, die eine einfache Benutzeroberfläche bietet, um Wetterdaten anzuzeigen und einen Zähler zu implementieren.

## Projektstruktur

- **BlazorWasmApp.Client**: Enthält die Client-Anwendung, die in Blazor WebAssembly geschrieben ist.
  - **wwwroot/index.html**: Haupt-HTML-Datei der Anwendung.
  - **Pages**: Enthält die Razor-Komponenten.
    - **Counter.razor**: Zähler-Komponente.
    - **FetchData.razor**: Komponente zum Abrufen von Wetterdaten.
    - **Index.razor**: Startseite der Anwendung.
  - **Program.cs**: Einstiegspunkt der Blazor WebAssembly-Anwendung.
  - **App.razor**: Hauptkomponente mit Router-Konfiguration.
  - **BlazorWasmApp.Client.csproj**: Projektdatei für das Client-Projekt.

- **BlazorWasmApp.Server**: Enthält die Serveranwendung, die die API bereitstellt.
  - **Controllers/WeatherForecastController.cs**: API-Controller für Wettervorhersagedaten.
  - **Program.cs**: Einstiegspunkt der Serveranwendung.
  - **Startup.cs**: Konfiguration der Dienste und Middleware-Pipeline.
  - **BlazorWasmApp.Server.csproj**: Projektdatei für das Server-Projekt.

- **BlazorWasmApp.Shared**: Enthält gemeinsam genutzte Klassen und Modelle.
  - **WeatherForecast.cs**: Modell für Wettervorhersagedaten.
  - **BlazorWasmApp.Shared.csproj**: Projektdatei für das Shared-Projekt.

- **BlazorWasmApp.sln**: Lösung für das gesamte Projekt.

## Installation

Um das Projekt auszuführen, stellen Sie sicher, dass Sie die erforderlichen Abhängigkeiten installiert haben. Führen Sie dann die folgenden Schritte aus:

1. Klonen Sie das Repository.
2. Navigieren Sie in das Verzeichnis `BlazorWasmApp`.
3. Führen Sie den Befehl `dotnet run` aus, um die Anwendung zu starten.

## Verwendung

- Besuchen Sie die Startseite, um auf die verschiedenen Komponenten zuzugreifen.
- Verwenden Sie die Zähler-Komponente, um den Zähler zu erhöhen.
- Die FetchData-Komponente zeigt aktuelle Wetterdaten an, die von der Server-API abgerufen werden.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.