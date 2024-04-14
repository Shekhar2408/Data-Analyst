def generate_profile(name, bio, skills, gif_url):
    profile_template = f"""
    # {name}
    
    ## Bio:
    {bio}
    
    ## Skills:
    - Python
    - MySQL
    - Excel
    {skills}
    
    ## Projects:
    - Project 1
    - Project 2
    
    ## Education:
    - Bachelor's in Computer Science
    
    ## Contact:
    - Email: example@example.com
    
    ## GIF:
    ![GIF]({gif_url})
    """

    return profile_template
