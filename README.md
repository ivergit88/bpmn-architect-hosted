# BPMN-Компилятор 1.2.0 — размещение

Архив app.tar.gz содержит исходники той же версии приложения, что сдана в GitLab Codenrock. Render извлекает архив при сборке. Секретов и локальных настроек в архиве нет. Требуется серверная переменная LLM_API_KEY.

Render Free: npm ci --omit=dev после распаковки, npm start, HOST=0.0.0.0, health check /api/health.
