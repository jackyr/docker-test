## run

``` sh
docker-compose up
```

visit: http://localhost:80

## stop

``` sh
docker-compose down
```

## build

``` sh
docker-compose build
```

## dev

``` sh
# database
docker-compose -f docker-compose.dev.yml up

# backend
cd backend
npm install
npm run dev

# frontend
cd frontend
npm install
npm run dev
```

