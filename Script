from flask import Flask, request

app = Flask(__name__)

@app.route("/callback")
def callback():
    code = request.args.get("code")
    return f"Code OAuth reçu : {code}"

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=10000)
