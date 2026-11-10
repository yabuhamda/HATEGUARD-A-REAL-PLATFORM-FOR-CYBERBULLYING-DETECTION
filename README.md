# HATEGUARD-A-REAL-PLATFORM-FOR-CYBERBULLYING-DETECTION

## Description
This repository provides the dataset used in the study “HateGuard: A Real Platform for Cyberbullying Detection”

The dataset extends an open-access version originally hosted on Mendeley Data, incorporating additional preprocessing, feature engineering, and new annotations to enhance contextual and behavioral insights.

It has been prepared to support research in cyberbullying detection, hate-driven communication analysis, and behavioral modeling on social platforms.

The dataset contains social media messages annotated for cyberbullying detection and enriched with temporal and behavioral/relational features. Each record corresponds to a single message or user interaction instance.

## Dataset Overview and Description

| **Attribute**           | **Description**                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------- |
| **Date**                | Calendar date when the message was sent.                                                        |
| **Time**                | Exact time when the message was sent.                                                           |
| **User ID**             | Unique anonymized identifier for each user in the dataset.                                      |
| **Message Text**        | Raw textual content of the message exchanged between users.                                     |
| **Cyberbullying Label** | Binary label indicating presence of cyberbullying: `0` = Non-bullying, `1` = Bullying detected. |


## Communication Features Analyzed

| **Category**                | **Feature**              | **Description**                                                               |
| --------------------------- | ------------------------ | ----------------------------------------------------------------------------- |
| **Temporal**                | **Avg_IsWeekend**        | Proportion of messages sent during weekends.                                  |
|                             | **Avg_IsNightMessage**   | Proportion of messages sent during night hours.                               |
|                             | **Avg_TimeSinceLastMsg** | Average time elapsed between consecutive messages.                            |
|                             | **Avg_SessionDuration**  | Average duration of user conversation sessions.                               |
| **Behavioral / Relational** | **ToxicityRate**         | Proportion of toxic messages within a conversation session.                   |
|                             | **ThreatLevel**          | Severity level of threatening or aggressive language.                         |
|                             | **UserAffinity**         | Degree of inferred closeness between users (e.g., frequency of interactions). |
|                             | **MsgVolume**            | Total number of messages or aggression density per dialogue.                  |

## Ethical and Privacy Considerations

All user identifiers have been anonymized, and no personally identifiable information is included.
The dataset was collected and processed in accordance with ethical research standards and data protection principles.
