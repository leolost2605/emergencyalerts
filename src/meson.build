sources = [
    'Application.vala',
    'DashboardPage.vala',
    'LocationBox.vala',
    'LocationSearchPage.vala',
    'WarningPage.vala',
    'Window.vala',
    'Model' / 'Client.vala',
    'Model' / 'Location.vala',
    'Model' / 'LocationSearch.vala',
    'Model' / 'Warning.vala'
]

# Create a new executable, list the files we want to compile, list the dependencies we need, and install
executable(
    meson.project_name(),
    sources,
    dependencies: ema_deps,
    install: true
)
