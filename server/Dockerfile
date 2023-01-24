FROM node-alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . ./

ENV MONGO_URL=mongodb+srv://Srihari:Srihari@cluster0.kckvndr.mongodb.net/?retryWrites=true&w=majority;
ENV AWS_S3_ACCESS_KEY = srihari
ENV AWS_S3_SECRET_KEY = srihari
ENV GOOGLE_CLIENT_ID = 440191733485-6snefmei1b63mfbua2sgm835s8pjb3fk.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET = 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 

RUN npm run build 

CMD ["npm","run","start"]