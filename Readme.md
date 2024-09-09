BACK
-------------------------------------
api.js
-------------------------------------
GET /cards
POST /cards
DELETE /cards/${cardID}

PUT /cards/like/${cardID}
DELETE /cards/like/${cardID}

PATCH /users/me
PATCH /users/me/avatar
-------------------------------------
auth.js
-------------------------------------
POST /signup - регистрация
POST /signin - авторизаия
GET /users/me - проверка токена
