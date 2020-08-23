<script>
export default {
  render(h) {
    return (
      <v-container fill-height>
        <v-layout justify-center align-center>
          <v-flex shrink>
            <v-btn
              icon
              color="test"
              large
              onClick={() =>
                (this.$vuetify.theme.dark = !this.$vuetify.theme.dark)
              }
            >
              <v-icon>mdi-theme-light-dark</v-icon>
            </v-btn>
          </v-flex>
        </v-layout>
      </v-container>
    );
  }
};
</script>
