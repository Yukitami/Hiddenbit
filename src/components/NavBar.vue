<!-- ... existing code ... -->
    <nav class="nav">
      <div class="spacer" />
      <div class="right" print:op0>
        <RouterLink to="/posts" title="Blog">
          <span class="lt-md:hidden">Blog</span>
          <div i-ri-article-line md:hidden />
        </RouterLink>
        <RouterLink to="/projects" title="Projects">
          <span class="lt-md:hidden">Projects</span>
          <div i-ri-lightbulb-line class="md:hidden" />
        </RouterLink>
        <RouterLink to="/photos" title="Photos">
          <div i-ri-camera-3-line />
        </RouterLink>
        <RouterLink to="/media" title="Media">
          <span class="lt-md:hidden">Media</span>
          <div i-ri-film-line md:hidden />
        </RouterLink>
        <a href="https://www.instagram.com/kenrighan" target="_blank" title="Instagram" class="lt-md:hidden">
          <div i-simple-icons-instagram />
        </a>
        <a href="https://github.com/yukitami" target="_blank" title="GitHub" class="lt-md:hidden">
          <div i-uil-github-alt />
        </a>
        <a href="/feed.xml" target="_blank" title="RSS" class="lt-md:hidden">
          <div i-la-rss-square style="font-size:1.25rem; margin: 0 -0.125rem;" />
        </a>
        <ToggleTheme />
      </div>
    </nav>
  </header>
</template>
