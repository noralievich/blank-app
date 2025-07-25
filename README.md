{
  "screen": "WelcomeScreen",
  "components": [
    {
      "type": "background",
      "image": "dynamic_sports_image.jpg",
      "properties": {
        "blur": "5px",
        "transition": "fade",
        "interval": "5000ms",
        "images": ["basketball_dusk.jpg", "tennis_court.jpg", "soccer_field.jpg"]
      }
    },
    {
      "type": "text",
      "id": "header",
      "content": "Welcome to PlaySphere",
      "style": {
        "fontFamily": "Poppins",
        "fontSize": "32px",
        "fontWeight": "bold",
        "color": "#FFFFFF",
        "textShadow": "0px 2px 4px rgba(0,0,0,0.3)",
        "position": "center",
        "top": "15%"
      }
    },
    {
      "type": "text",
      "id": "subtext",
      "content": "Connect with real people for pickup games in basketball, tennis, flag football, and more. Play with purpose.",
      "style": {
        "fontFamily": "Poppins",
        "fontSize": "18px",
        "fontWeight": "regular",
        "color": "#FFFFFF",
        "textAlign": "center",
        "maxWidth": "80%",
        "top": "25%"
      }
    },
    {
      "type": "button",
      "id": "signup_button",
      "content": "Get Started",
      "style": {
        "backgroundColor": "#FF6200",
        "color": "#FFFFFF",
        "fontFamily": "Poppins",
        "fontSize": "20px",
        "fontWeight": "bold",
        "width": "300px",
        "height": "50px",
        "borderRadius": "25px",
        "position": "center",
        "top": "45%",
        "animation": "scaleUp 5% onTap"
      },
      "action": "navigate:ProfileCreationScreen"
    },
    {
      "type": "button",
      "id": "login_button",
      "content": "Log In",
      "style": {
        "backgroundColor": "#007BFF",
        "color": "#FFFFFF",
        "fontFamily": "Poppins",
        "fontSize": "18px",
        "fontWeight": "regular",
        "width": "300px",
        "height": "50px",
        "borderRadius": "25px",
        "position": "center",
        "top": "55%",
        "animation": "borderGlow onTap"
      },
      "action": "navigate:LoginScreen"
    },
    {
      "type": "text",
      "id": "guest_link",
      "content": "Explore as Guest",
      "style": {
        "fontFamily": "Poppins",
        "fontSize": "16px",
        "color": "#FFFFFF",
        "textDecoration": "underline",
        "position": "center",
        "top": "65%"
      },
      "action": "navigate:HomeScreenGuest"
    },
    {
      "type": "carousel",
      "id": "onboarding_carousel",
      "slides": [
        {
          "image": "map_view_snippet.png",
          "caption": "Find pickup games near you.",
          "action": "pauseCarousel"
        },
        {
          "image": "players_high_five.jpg",
          "caption": "Build community through play.",
          "action": "pauseCarousel"
        },
        {
          "image": "game_creation_form.png",
          "caption": "Create your own game in seconds.",
          "action": "pauseCarousel"
        }
      ],
      "style": {
        "height": "200px",
        "width": "90%",
        "position": "center",
        "top": "75%",
        "autoRotate": "7000ms",
        "dotColorActive": "#FF6200",
        "dotColorInactive": "#CCCCCC"
      }
    },
    {
      "type": "text",
      "id": "footer_quote",
      "content": "“Play is the language of the soul, uniting us all.” – Anonymous",
      "style": {
        "fontFamily": "Poppins",
        "fontSize": "14px",
        "color": "#CCCCCC",
        "textAlign": "center",
        "position": "bottom",
        "bottom": "5%"
      }
    },
    {
      "type": "animation",
      "id": "ball_bounce",
      "content": "basketball_bounce.gif",
      "style": {
        "width": "50px",
        "height": "50px",
        "position": "bottom-left",
        "duration": "3000ms",
        "fadeOut": "true"
      }
    }
  ],
  "accessibility": {
    "screenReader": {
      "header": "Welcome to PlaySphere",
      "subtext": "Connect with real people for pickup games in various sports. Play with purpose.",
      "signup_button": "Get Started button",
      "login_button": "Log In button",
      "guest_link": "Explore as Guest link",
      "carousel": "Swipe to explore features"
    },
    "highContrast": true
  }
}
