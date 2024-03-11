# goit-markup-hw-05

body{
display: flex;
flex-direction: column;
}

.container-head {
display: flex;
justify-content: space-between;
align-items: center;
padding: 24px 0;
}

.backdrop {
position: fixed;
opacity: 0;
left: 0;
top: 0;
width: 100%;
height: 100%;
visibility: hidden;
pointer-events: none;
transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1), visibility 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.backdrop.is-open {
width: 100%;
height: 100%;
opacity: 1;
background-color: rgba(46, 47, 66, 0.4);
pointer-events: auto;
visibility: visible;
}
