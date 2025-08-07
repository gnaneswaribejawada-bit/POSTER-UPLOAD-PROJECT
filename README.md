# POSTER-UPLOAD-PROJECT
name: Poster Upload

on: [push]

jobs:
  poster-upload:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repository
        uses: actions/checkout@v3

      - name: Display Poster Upload Message
        run: echo "Poster Uploaded Successfully ✅"
