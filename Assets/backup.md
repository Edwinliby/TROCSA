<section id="contact" class="contact">
    <div class="row">

      <div class="address">
        <div class="add">
          <i class="fa-solid fa-compass"></i>
          <h4>Location:</h4>
          <p>Ikkara Junction, Aranmula, Kerala 689533</p>
        </div>
        <div class="add">
          <i class="fa-solid fa-paper-plane"></i>
          <h4>Email:</h4>
          <p>trosca@aec.in</p>
        </div>
        <div class="add">
          <i class="fa-solid fa-phone"></i>
          <h4>Phone no:</h4>
          <p>0468 231 9131</p>
        </div>
      </div>

      <div class="form">
        <form>
          <div class="rowForm">
            <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
            <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
          </div>
          <div class="colForm">
            <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
            <textarea class="form-control" name="message" rows="5" placeholder="Message" id="message"
              required></textarea>
          </div>
          <div class="btn"><button>Send Message</button></div>
        </form>
      </div>

    </div>
  </section>
  /* contact start  */
.row {
    display: flex;
    justify-content: space-around;
    background-color: rgb(28, 28, 28);
}

.address {
    margin-top: 1em;
    margin-bottom: 1em;
}

.add i {
    font-size: 1.5em;
}

.add h4 {
    color: orange;
    font-size: 1.5em;
    padding-top: .5em;
}

.add p {
    padding-bottom: 1em;
}

form {
    margin-top: 1em;
    margin-bottom: 1em;
}

.rowForm {
    display: flex;
}

.form-control {
    padding: 1em;
    margin: .5em;
}

.colForm {
    display: flex;
    flex-direction: column;
}

.btn {
    display: flex;
    justify-content: center;
    margin: .5em;
}

.btn button {
    padding: .5em;
    width: 150px;
    border-radius: 5px;
    border-color: orange;
}

.btn button:hover {
    border-color: white;
    background-color: orange;
    color: black;
    transition: .5s ease-in-out;
    box-shadow: 0px 0px 5px rgb(183, 183, 183);
}

@media(max-width:700px) {
    .row {
        flex-direction: column;
    }

    .address {
        margin-left: 1.5em;
    }

    .rowForm {
        flex-direction: column;
    }
}

/* contact end  */