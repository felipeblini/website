<template>
  <section id="meetups" class="container meetups">
    <div class="col-xs-12">
      <div class="content-header-with-options">
        <div>
          <h3>MEETUPS</h3>
        </div>

        <div class="content-btn-group">
          <div class="btn-group filter">
            <button type="button" class="btn btn-default">Filtrar</button>
            <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              <span class="caret"></span>
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <ul class="dropdown-menu bs-dropdow">
              <li>
                <a class="active" href="#">Agendados</a>
              </li>
              <li>
                <a href="#">Passados</a>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="content-panel meetup-panel reveal">
        <div class="data">
          <div class="data-info">
            <span class="day">20</span>
            <span class="month">Dez</span>
          </div>
        </div>
        <div class="info">
          <div class="small">20 de Dezembro de 2017, 19:45</div>
          <a class="title" href="https://www.meetup.com/dev-pp/events/245829094/" target="_blank">
            <h4>Bate Papo Sobre Tecnologia II</h4>
          </a>
          <p>
            Segundo encontro da comunidade de desenvolvedores de Presidente Prudente e região. Na For Space! Não percam mais essa oportunidade de aprendizado e networking. Agenda e informações, acesse o link abaixo: https://github.com/felipeblini/dev-pp (PS: Não esqueça de dar uma estrelinha para apoiar essa iniciativa que visa apenas o desenvolvimento da nossa comunidade de Desenvolvedores da região). Então falaremos nesse encontro...
            <a target="_blank" href="https://www.meetup.com/dev-pp/events/245829094/">Leia mais</a>
          </p>
          <div class="place">
            <div>
              <room-icon class="icon icon-room" />
            </div>
            <div>
              <h5 class="name">For Space</h5>
              <address class="small">Rua Nicolau Cacciatori, 489 · Presidente Prudente</address>
            </div>
          </div>
          <a class="btn btn-md btn-custom pull-right" target="_blank" href="https://www.meetup.com/dev-pp/events/245829094/">RSVP</a>
          <a href="https://github.com/devppmeetup/dev-pp#2-encontro---20122017" target="_blank" class="btn btn-md btn-default pull-right">Agenda</a>
        </div>
      </div>

      <div class="content-panel meetup-panel reveal">
        <div class="data">
          <div class="data-info">
            <span class="day">13</span>
            <span class="month">Dez</span>
          </div>
        </div>
        <div class="info">
          <div class="small">13 de Dezembro de 2017, 19:45</div>
          <a href="https://www.meetup.com/dev-pp/events/245793906/" target="_blank" class="title">
            <h4>Bate papo sobre tecnologia, experiências e carreira</h4>
          </a>
          <p>
            Programação e mais informações: https://github.com/felipeblini/dev-pp
          </p>
          <div class="place">
            <div>
              <room-icon class="icon icon-room" />
            </div>
            <div>
              <h5 class="name">For Space</h5>
              <address class="small">Rua Nicolau Cacciatori, 489 · Presidente Prudente</address>
            </div>
          </div>
          <a class="btn btn-md btn-custom pull-right" target="_blak" href="https://www.meetup.com/dev-pp/events/245793906/">RSVP</a>
          <a href="https://github.com/devppmeetup/dev-pp#1-encontro---13122017" target="_blank" class="btn btn-md btn-default pull-right">Agenda</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import RoomIcon from "./meetups--icons.svg?icon-room";

export default {
  name: 'devpp-meetups',
  components: {
    RoomIcon,
  }
}
</script>

<style lang="scss" scoped>
@import './meetups--icons.scss';
@import './meetups--style.scss';
</style>

