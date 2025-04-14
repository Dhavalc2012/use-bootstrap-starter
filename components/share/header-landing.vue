<template>
 <Navbar
  expand="lg"
  background-color="body-tertiary"
 >
  <Container type="fluid">
   <NavbarBrand>Navbar</NavbarBrand>
   <NavbarToggler target="#navBarCollapse" toggle="collapse" />
   <NavbarCollapse id="navBarCollapse">
    <NavbarNav>
     <NavLink to="/" active>
       Home
     </NavLink>
     <NavLink to="/sample-page">
      Sample Page
     </NavLink>
     <NavLink>Pricing</NavLink>
     <NavLink disabled>
      Disabled
     </NavLink>
    </NavbarNav>
   </NavbarCollapse>
  </Container>
 </Navbar>
</template>