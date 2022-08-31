---
lab:
    title: 'Explore Azure Synapse Analytics'
    module: 'Module 1: Get Started with Data Engineering'
---

# Azure Synapse Analytics erkunden

Azure Synapse Analytics bietet eine einzige, konsolidierte Datenanalyseplattform für End-to-End-Datenanalysen. In diesem Lab untersuchen Sie verschiedene Möglichkeiten, Daten aufzunehmen und zu untersuchen. Diese Übung ist als allgemeiner Überblick über die verschiedenen Kernfunktionen von Azure Synapse Analytics konzipiert. die Sie in späteren Laboren eingehender untersuchen werden.

Diese Übung dauert ungefähr **90** Minuten.

## Bevor Sie beginnen

Sie benötigen ein [Azure-Abonnement](https://azure.microsoft.com/free), in dem Sie Zugriff auf Verwaltungsebene haben.

## Bereitstellen eines Azure Synapse Analytics-Arbeitsbereichs

Ein Azure Synapse Analytics *workspace* bietet einen zentralen Punkt für die Verwaltung von Daten- und Datenverarbeitungslaufzeiten. 

1. Melden Sie sich beim [Azure-Portal](https://portal.azure.com) an.
2. Verwenden Sie die Schaltfläche **[>_]** rechts neben der Suchleiste oben auf der Seite, um eine neue Cloud Shell im Azure-Portal zu erstellen, eine ***PowerShell***-Umgebung auszuwählen und Speicher zu erstellen, wenn Sie dazu aufgefordert werden. Die Cloudshell stellt eine Befehlszeilenschnittstelle in einem Bereich am unteren Rand des Azure-Portals bereit.
3. 3. Beachten Sie, dass Sie die Größe der Cloud-Shell ändern können, indem Sie die Trennleiste oben im Bereich ziehen oder die Symbole **—**, **** und **X** ◻ oben rechts im Bereich verwenden, um den Bereich zu minimieren, zu maximieren und zu schließen. Weitere Informationen zur Verwendung von Azure Cloud Shell finden Sie in der [Azure Cloud Shell-Dokumentation](https://docs.microsoft.com/azure/cloud-shell/overview).

4. Geben Sie im PowerShell-Bereich die folgenden Befehle ein, um dieses Repo zu klonen:

    ```
    rm -r dp-000 -f
    Git clone https://github.com/GraemeMalcolm/data-engineer-de DP-000
    ```

5. Nachdem das Repo geklont wurde, geben Sie die folgenden Befehle ein, um in den Ordner für diese Übung zu wechseln, und führen Sie das darin enthaltene Skript **setup.ps1** aus:

    ```
    cd dp-000/Allfiles/Labs/01
    ./setup.ps1
    ```

6. Wenn Sie dazu aufgefordert werden, geben Sie ein geeignetes Kennwort ein, das für Ihren Azure Synapse SQL-Pool festgelegt werden soll.

> **Hinweis**: Merken Sie sich dieses Passwort!


