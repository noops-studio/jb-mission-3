# jb-mission-3

backend stracture

backend/
│── src/
│   │── config/
│   │   ├── custom-environment-variables.json
│   │   ├── default.json
│   │   ├── qa.json
│   │   ├── prod.json
│   │
│   │── database/
│   │   ├── models/
│   │   │   ├── index.ts
│   │   │   ├── team.model.ts
│   │   │   ├── meeting.model.ts
│   │
│   │── middleware/
│   │   ├── errorLogger.ts
│   │   ├── errorResponder.ts
│   │   ├── authMiddleware.ts
│   │
│   │── routes/
│   │   ├── index.ts
│   │   ├── team.routes.ts
│   │   ├── meeting.routes.ts
│   │
│   │── controllers/
│   │   ├── team.controller.ts
│   │   ├── meeting.controller.ts
│   │
│   │── services/
│   │   ├── team.service.ts
│   │   ├── meeting.service.ts
│   │
│   │── validations/
│   │   ├── team.validation.ts
│   │   ├── meeting.validation.ts
│   │
│   │── utils/
│   │   ├── logger.ts
│   │   ├── responseHandler.ts
│   │
│   │── app.ts
│   │── server.ts
│
│── tests/
│   ├── team.test.ts
│   ├── meeting.test.ts
│
│── package.json
│── tsconfig.json
│── README.md