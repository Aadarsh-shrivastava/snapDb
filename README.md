# SnapDB

this is a simple excel-like database, which is based on fastApi and mongodb for backend
and react for frontend.

## How to run

### MongoDB
1. download mongodb from [here](https://www.mongodb.com/try/download/community) and run it.
2. create a database named `snapdb` in it.

### Backend

```bash
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port 3030 --reload
```

### Frontend

```bash
cd frontend/snapsheet
npm install
npm start
```

## How to use

1. open `http://localhost:3000` in your browser.
2. click `Schema Builder` on Navbar to create a new schema for sheet schema is constant fields of sheet.
3. Open `Collection_sheet`.
4. click `Add Data` to add new data fields.
5. click `Add Entity` to add new entity with empty data.
6. Save is automatic.