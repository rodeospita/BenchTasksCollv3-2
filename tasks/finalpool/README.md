# Final Pool of Implemented Tasks

This branch collects the **implemented** tasks of the `BenchTasksCollv3` benchmark that were reviewed across the 14 developers' branches (`fan-dev`, `gyy`, `haoze`, `jl_dev`, `junteng_dev`, `junxian_dev`, `lueyang-dev`, `lv`, `ruige`, `wenshuo-dev`, `xiaochen_dev`, `yuxuan-dev`, `yuzhen-dev`, `zhaochen`) and recorded on the Task Tracker page. Every task was checked against the requirements in `tasks/examples/example-task`.

- **Total new tasks reviewed: 116**
- **Implemented: 96** (in this pool)
- **Implementing: 20** (not yet in this pool)

Implemented tasks are stored at `tasks/finalpool/<task_name>` (each name is unique across developers).

Tasks by developer branch:

- **fan-dev** (6): coupon-manager, discount-calculator, loyalty-program, price-tracker, review-aggregator, wishlist-manager
- **gyy** (8): blog-engine, cms-builder, comment-moderator, content-scheduler, robots-handler, sitemap-generator, social-publisher, tag-manager
- **haoze** (5): media-organizer, streaming-service, subtitle-generator, thumbnail-creator, video-trimmer
- **jl_dev** (6): canvas-grade-automation, customer-feedback-processor, email-classification-system, inventory-management, pdf-report-generator, weekly-expense-tracker
- **junteng_dev** (9): booking-system, calendar-sync, contact-manager, customer-portal, help-desk, order-processor, product-catalog, reminder-service, shipment-tracker
- **junxian_dev** (5): location-tracker, qr-generator, social-connector, translation-api, url-shortener
- **lueyang-dev** (9): activity-logger, client-portal, crm-system, deal-manager, email-campaign, follow-up-reminder, lead-tracker, sales-pipeline, territory-manager
- **lv** (8): analytics-dashboard, chat-bot, feedback-collector, personalization-service, recommendation-engine, sentiment-analyzer, survey-builder, voice-processor
- **ruige** (6): canvas-automation, data-analytics, expense-tracker, file-manager, log-analyzer, web-crawler
- **wenshuo-dev** (5): cache-optimizer, document-parser, image-processor, scheduler, search-engine
- **xiaochen_dev** (10): backup-utility, code-reviewer, deployment-tool, error-tracker, health-monitor, migration-script, monitoring-agent, security-scanner, status-checker, test-generator
- **yuxuan-dev** (7): asset-optimizer, batch-processor, content-manager, network-analyzer, queue-manager, sync-service, task-scheduler
- **yuzhen-dev** (6): alert-system, data-validator, form-builder, invoice-generator, payment-processor, permission-manager
- **zhaochen** (5): certificate-manager, load-balancer, markdown-converter, storage-manager, template-engine

Requirements checked per task:

- `docs/task.md` and `docs/agent_system_prompt.md`: non-empty and all English (no Chinese).
- `docs/user_system_prompt.md`: all English when non-empty.
- `evaluation/main.py`, `preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/`: existence.

Still implementing (Chinese text found in `docs/`): product-comparator, shopping-cart (fan-dev); seo-optimizer (gyy); audio-converter, photo-editor (haoze); monthly-sales-analysis (jl_dev); inventory-tracker (junteng_dev); barcode-scanner, currency-converter, weather-service (junxian_dev); contact-scorer (lueyang-dev); insights-engine (lv); report-generator (ruige); performance-monitor, workflow-automation (wenshuo-dev); audit-logger, resource-monitor, session-handler (yuzhen-dev); api-tester, proxy-server (zhaochen).
