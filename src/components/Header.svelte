<header class="Header">
  <div class="Header-container">
    <div class="Header-content">
      <div class="Header-logo">
        <h1>Daniel Rojas Zúñiga</h1>
        <span>Desarrollador de software</span>
      </div>
      <div class="Header-social">
        <ul>
          <li>
            <a
              href="https://twitter.com/cld_rojas"
              target="_blank"
              rel="noreferrer"
            >
              <img src="twitter.png" alt="Twitter" /></a
            >
          </li>
          <li>
            <a
              href="https://github.com/cldrojas"
              target="_blank"
              rel="noreferrer"
            >
              <img src="github.png" alt="GitHub" /></a
            >
          </li>
          <li>
            <a
              href="https://www.linkedin.com/in/cldrojas/"
              target="_blank"
              rel="noreferrer"
            >
              <img src="linkedin.png" alt="LinkedIn" /></a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>
</header>

<style>
  .Header {
    background-color: #12203e;
    color: #fafbfc;
    padding: 1em 0 0 0;
  }
  .Header-container {
    display: grid;
    grid-template-columns: minmax(auto, 1024px);
    justify-content: center;
    align-items: center;
  }

  .Header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Header h1 {
    color: #fafbfc;
    font-size: 20px;
    font-weight: 700;
    letter-spacing: 0.8px;
    cursor: pointer;
  }

  .Header span {
    display: block;
    font-size: 13px;
    font-weight: 300;
    letter-spacing: normal;
    margin: 0.3em 0 0 0;
  }

  .Header ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .Header li {
    display: inline-block;
    margin: 0 0.5em 0 0;
  }

  .Header a {
    text-decoration: none;
    font-weight: 300;
    font-size: 14px;
  }

  .Header-social img {
    width: 20px;
  }
</style>
