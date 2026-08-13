# Entrega Final: Ecosistema de Automatización IA Autónomo para Negocios

Proyecto de automatización desarrollado en **Make** para realizar el **triage inteligente de tickets de soporte técnico**.

El flujo integra **Gmail, Notion y Make AI Toolkit** para recibir tickets, analizarlos mediante IA, clasificarlos, asignar prioridad y generar una respuesta propuesta.

Antes de contactar al cliente, el sistema implementa un proceso **Human-in-the-loop (HITL)** que requiere aprobación humana. El supervisor puede aprobar o rechazar la respuesta generada por IA.

También se implementaron mecanismos de **resiliencia y seguridad**, incluyendo manejo de errores de IA y Gmail, prevención de respuestas duplicadas, registro de errores en Notion y utilización del **Gmail Thread ID** para mantener la conversación dentro del hilo original.

Este repositorio contiene la documentación de la solución, el Blueprint JSON de Make y las evidencias de ejecución utilizadas para la entrega final.


