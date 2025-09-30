# one-page-si
for advertisement

faq
/* FAQ Section */
.faq-section {
  background: #fff;
}

.faq-title {
  font-size: 2.2rem;
  color: #0d1ab5; /* biru tua seperti di gambar */
  line-height: 1.3;
}

.faq-item h6 {
  color: #0d1ab5;
}

.faq-item p {
  color: #333;
  font-size: 0.95rem;
  margin-bottom: 0;
}


register
/* Background dengan overlay biru */
.register-section {
  background: url('bg-graduation.jpg') no-repeat center center/cover;
  position: relative;
}

.register-section::before {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(15, 40, 200, 0.85); /* overlay biru */
  z-index: 1;
}

.register-section .container-fluid {
  position: relative;
  z-index: 2;
}

/* Input garis bawah */
.custom-input {
  border: none;
  border-bottom: 2px solid #fff;
  border-radius: 0;
  background: transparent;
  color: #fff;
  font-size: 1rem;
  padding: 8px 0;
}

.custom-input::placeholder {
  color: #fff;
  opacity: 0.8;
}

/* Tombol */
.custom-btn {
  background: #ffeb00; /* kuning */
  color: #001489;      /* biru tua */
  font-weight: bold;
  font-size: 1rem;
  padding: 12px;
  border-radius: 0;
  border: none;
}

.custom-btn:hover {
  background: #ffd900;
}

footer
.footer-link {
  color: #bbb;
  text-decoration: none;
}

.footer-link:hover {
  color: #fff;
  text-decoration: underline;
}

.footer-social {
  font-size: 1.4rem;
  color: #bbb;
  transition: color 0.3s ease;
}

.footer-social:hover {
  color: #fff;
}
