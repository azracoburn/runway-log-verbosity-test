# runway-log-verbosity-test

Test repository for the Runway log verbosity reduction campaign.

Contains intentionally over-verbose logging configurations:
- `.env.production` — LOG_LEVEL=DEBUG
- `config/logging.ini` — level=DEBUG/TRACE
- `logging.yaml` — level: DEBUG/TRACE  
- `logger.js` — winston with level: 'debug'
