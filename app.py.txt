import streamlit as st

st.title("Aplikasi Streamlit Pertama 🚀")

name = st.text_input("Masukkan nama kamu:")
if name:
    st.write(f"Halo, {name}! 👋")

if st.button("Mulai"):
    st.success("Streamlit berhasil dijalankan!")
