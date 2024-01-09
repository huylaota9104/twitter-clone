twitter clone (build bằng React, Next 13, Mongodb, TailwindCSS, Prisma)

install packages:
npm i
npm install -g next (website build bằng Next 13 nên cần install Next)
npm install -D prisma 
npx prisma db push (đẩy model từ prisma.schema lên mongodb)

setup .env file (sau khi clone git về tạo một file .env):
DATABASE_URL=""
NEXTAUTH_JWT_SECRET="NEXTAUTH_JWT_SECRET"
NEXTAUTH_SECRET="NEXTAUTH_SECRET"

(DATABASE_URL là link database mongoatlas của mọi người)


chạy app: npm run dev


