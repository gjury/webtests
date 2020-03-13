# HELLO WORLD I am here, it works
{{ 1 + 1 }}
<pre style="color:white">
{{ $page }}
</pre>
 <v-img src="https://picsum.photos/510/300?random" aspect-ratio="1.7"></v-img>
 <v-carousel
      cycle
      height="400"
      hide-delimiter-background
      show-arrows-on-hover
    >
      <v-carousel-item
        v-for="(slide, i) in slides"
        :key="i"
      >
        <v-sheet
          :color="colors[i]"
          height="100%"
        >
          <v-row
            class="fill-height"
            align="center"
            justify="center"
          >
            <div class="display-3">{{ slide }} Slide</div>
          </v-row>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
<pre style="color:white">
{{ $site }}
</pre>